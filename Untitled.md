

```dataviewjs
const journalPath = '"01 - Personal/Daily"'; // Chemin vers tes notes
const chartColor = '#4287f5'; // Couleur du graphique

// Liste des mois (labels et indices pour filtrage)
const months = [
    { label: "Janvier", index: 0 },
    { label: "Février", index: 1 },
    { label: "Mars", index: 2 },
    { label: "Avril", index: 3 },
    { label: "Mai", index: 4 },
    { label: "Juin", index: 5 },
    { label: "Juillet", index: 6 },
    { label: "Août", index: 7 },
    { label: "Septembre", index: 8 },
    { label: "Octobre", index: 9 },
    { label: "Novembre", index: 10 },
    { label: "Décembre", index: 11 }
];

// Crée un div pour afficher le graphique
const chartContainer = document.createElement('div');
chartContainer.style.height = '400px';  // Taille du graphique, ajustable
this.container.appendChild(chartContainer);

// Fonction pour générer le graphique pour un mois donné
function renderGraph(monthIndex) {
    const startDate = moment(`2024-${String(monthIndex + 1).padStart(2, '0')}-01`);
    const endDate = startDate.clone().endOf('month');
    var labels = [];
    var sleepData = [];

    // Générer les dates pour le mois sélectionné
    while (startDate.isSameOrBefore(endDate)) {
        labels.push(startDate.format("YYYY-MM-DD"));
        startDate.add(1, 'day');
    }

    // Récupérer les notes et extraire la métrique "Sleep"
    var dailyNotes = dv.pages(journalPath);
    labels.forEach(date => {
        let note = dailyNotes.find(n => n.file.name === date); // Trouve la note par nom de fichier
        let sleepValue = 0;  // Valeur par défaut si la métrique n'existe pas

        if (note) {
            // Vérifie si la métrique "Sleep" existe sous différentes formes
            if (note.Sleep) {
                sleepValue = note.Sleep; // Récupère la valeur de "Sleep" (au cas où c'est "Sleep: 6")
            } else if (note["Sleep::"]) {
                sleepValue = note["Sleep::"]; // Récupère la valeur de "Sleep::" (si c'est cette forme)
            }
        }

        sleepData.push(sleepValue); // Ajoute la valeur de "Sleep" (ou 0)
    });

    // Configuration du graphique
    const sleepChart = {
        type: 'line',
        data: {
            labels: labels,
            datasets: [{
                label: `Sleep Score (${months[monthIndex].label})`,
                data: sleepData,
                backgroundColor: [chartColor],
                borderColor: [chartColor],
                borderWidth: 2
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true,
                    max: 10
                }
            }
        }
    };

    // Efface le graphique précédent et rend le nouveau
    chartContainer.innerHTML = ""; // Efface le contenu précédent
    window.renderChart(sleepChart, chartContainer); // Utilise le conteneur pour afficher le graphique
}

// Ajouter une liste déroulante pour sélectionner le mois
const select = document.createElement('select');
months.forEach((month, index) => {
    const option = document.createElement('option');
    option.value = index;
    option.text = month.label;
    select.appendChild(option);
});

// Ajoute un événement pour changer de mois
select.addEventListener('change', (event) => {
    const selectedMonth = parseInt(event.target.value, 10);
    renderGraph(selectedMonth);
});

// Ajoute la liste déroulante avant le graphique
this.container.appendChild(select);

// Affiche le graphique initial (par défaut, janvier)
renderGraph(0);

```
