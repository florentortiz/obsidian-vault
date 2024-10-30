# 🗃️ Template de Vault Obsidian

Um template minimalista porém poderoso para organizar sua vault do Obsidian, focando em simplicidade e eficiência. Este sistema utiliza uma estrutura de pastas cuidadosamente limitada, complementada por um sistema robusto de tags e links.

## ✨ Características

- 📁 Hierarquia limitada a um nível de profundidade
- 🏷️ Sistema de tags abrangente e flexível
- 🔗 Uso estratégico de links e MOCs (Maps of Content)
- 📝 Templates prontos para diferentes tipos de notas
- 🚀 Fácil de começar, poderoso para escalar

## 🎯 Por que usar este template?

### Benefícios Principais
- **Simplicidade**: Máximo de dois cliques para acessar qualquer informação
- **Eficiência**: Reduz a "paralisia por análise" ao decidir onde armazenar notas
- **Flexibilidade**: Cresce organicamente com seu uso
- **Manutenção**: Fácil de manter e reorganizar quando necessário

## 🚀 Como Começar

1. Clone este repositório ou faça download como ZIP
2. Abra o Obsidian
3. Selecione "Open folder as vault" e escolha a pasta do template
4. Comece com `00 - Dashboard/Home.md` para entender a navegação
5. Verifique `99 - Meta/Organizacao/` para guias uteis e detalhados de como utilizar o sistema

## 📁 Estrutura de Pastas

```
.
├── 00 - Dashboard/         # Hub central da vault
├── 01 - Pessoal/           # Conteúdo pessoal e diário
│   ├── Diario/
│   ├── Fleeting/
│   ├── Planos/
│   ├── Reflexoes/
│   └── Saude/
├── 02 - Conhecimento/      # Notas de estudo por área
│   ├── Computacao/         # Exemplos de áreas de conhecimento
│   ├── Filosofia/
│   ├── Historia/
│   ├── Literatura/
│   └── Saude/
├── 03 - Projetos/          # Projetos em desenvolvimento
│   ├── Projeto1/
│   ├── Projeto2/
│   └── Projeto3/
├── 04 - Referencias/       # Material fonte e bibliografia
│   ├── Artigos/
│   ├── Cursos/
│   ├── Livros/
│   └── Tutoriais/
└── 99 - Meta/              # Sistema e templates
    ├── Templates/
    └── Organizacao/
```

## 🏷️ Sistema de Tags
verificar `99 - Meta/Organizacao/Como classificar notas com tags.md` para uma lista completa

### 1. Tags por Tipo
Identificam a natureza da nota:
```
#tipo/tarefa     → Tarefas
#tipo/projeto    → Projetos
#tipo/diario     → Anotações diárias
#tipo/estudo     → Material de estudo
#tipo/ideia      → Insights
#tipo/reflexao   → Reflexões
#tipo/habitos    → Rotinas e hábitos
```

### 2. Tags por Contexto
Indicam o ambiente da nota:
```
#contexto/estudos    → Aprendizado
#contexto/trabalho   → Profissional
#contexto/pessoal    → Desenvolvimento pessoal
#contexto/academico  → Universitário
#contexto/hobbies    → Interesses pessoais
```

### 3. Tags por Tema
Organizam por área de conhecimento:
```
Computação:
#tema/ciberseguranca → Segurança
#tema/dev           → Desenvolvimento
#tema/os           → Sistemas operacionais
#tema/algoritmos    → Algoritmos e estruturas
#tema/IA           → Inteligência artificial

...e muito mais (ver guia completo de tags)
```

### 4. Tags de Metadados
Controlam status e prioridade:
```
#estado/[concluido|em-progresso|planejamento|ideia]
#prioridade/[alta|media|baixa]
#revisao/[pendente|concluida|necessaria]
```

### Boas Práticas de Uso de Tags

#### Tags Mínimas Requeridas
Para manter a consistência e facilitar a busca, cada nota deve incluir no mínimo:
1. Uma tag de tipo (`#tipo/...`)
2. Uma tag de contexto (`#contexto/...`)
3. Uma tag de tema (`#tema/...`)
4. Uma tag de estado/prioridade quando aplicável

## 🔗 Sistema de Links

### Tipos de Links
1. **Links Diretos**: `[[Nome da Nota]]`
2. **Links com Alias**: `[[Nome da Nota|Texto Exibido]]`
3. **Links para Seções**: `[[Nome da Nota#Seção]]`

### Práticas Recomendadas
- Crie conexões significativas
- Use MOCs (Maps of Content) para organizar temas
- Aproveite backlinks para descobrir relações
- Construa hierarquias flexíveis através de links

## 📚 Métodos Integrados

O sistema incorpora práticas de:
- **Zettelkasten**: Notas atômicas interconectadas
- **PARA**: Projetos, Áreas, Recursos, Arquivos
- **Building a Second Brain**: Captura e organização de conhecimento
- **GTD**: Getting Things Done para gestão de tarefas

## ⚙️ Plugins Recomendados

### Essenciais:
- Iconize
- Homepage
- Dataview
- Calendar
- Backlinks
- Templates
- Daily Notes

### Opcionais:
- Tag Wrangler
- Graph Analysis
- Natural Language Dates
- Mind Map
- Kanban
- Templater
- Outliner

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:
1. Criar Issues com sugestões
2. Enviar Pull Requests com melhorias
3. Compartilhar suas experiências usando o template
4. Reportar bugs ou problemas

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

Este template foi inspirado por vários sistemas de gestão de conhecimento e pela comunidade Obsidian. Agradecimentos especiais a:
- Metodologia Zettelkasten
- Sistema PARA de Tiago Forte
- Comunidade do r/Obsidian