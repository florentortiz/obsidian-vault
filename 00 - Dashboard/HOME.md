# 🎯 Dashboard Pessoal

> [!quote] Pensamento do Dia
> "A vida é o que acontece enquanto você está ocupado fazendo outros planos." - John Lennon

> [!warning] **Aviso Importante**
> - Esta dashboard é apenas um exemplo, que pressupoe anotações
> - que nao existem no seu vault. Por favor, adapte ao seu uso.
> - Tome isto como inspiração para criar sua própria dashboard.


## 🌅 Links Rápidos
- [[Rotina|Minha Rotina]] 
- [[Treino|Programa de Treino]] 
- [[Dieta|Dieta]] 
- [[01 - Pessoal/Diario/{{date}}|Entrada de Hoje]] 
- [[Tasks|Tarefas Pendentes]]

## 🎯 Áreas de Foco

> [!info] Estudos Ativos
> - [[02 - Conhecimento/Computação/Cibersegurança|🔒 Cibersegurança]]
> - [[02 - Conhecimento/Computação/Desenvolvimento|💻 Desenvolvimento]]
> - [[02 - Conhecimento/Humanidades/Estoicismo|📚 Estoicismo]]

> [!tip] Projetos em Andamento
> - [[03 - Projetos/Projeto 1|🚀 Projeto Principal]]
> - [[03 - Projetos/Projeto 2|🎮 Game Dev]]
> - [[Tasks#Em Progresso|📋 Ver Todos]]

## 💪 Saúde & Bem-estar

> [!success] Rotinas & Hábitos
> ```dataview
> TASK FROM "01 - Pessoal/Rotina"
> WHERE !completed
> LIMIT 5
> ```

> [!note] Próximos Treinos
> ```dataview
> LIST FROM #tipo/treino AND #estado/em-progresso
> LIMIT 3
> ```

## 📚 Aprendizado Contínuo

> [!note] Últimas Notas de Estudo
> ```dataview
> TABLE file.ctime as "Criado"
> FROM "02 - Conhecimento"
> SORT file.ctime DESC
> LIMIT 3
> ```

---
## ⚡ Quick Capture
- [ ] Nova Tarefa
- [ ] Nova Ideia
- [ ] Novo Projeto

---
*Última atualização: {{date}}*