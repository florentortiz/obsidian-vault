# 🗃️ Obsidian Vault Template

A minimalist yet powerful template for organizing your Obsidian vault, focusing on simplicity and efficiency. The key feature of this system is its **intentionally flat structure** with a strict one-level depth hierarchy, complemented by a robust tagging and linking system.

## ✨ Features

- 📁 **Strictly Limited Hierarchy**: One-level depth maximum - no deep nested folders!
- 🏷️ Comprehensive and flexible tagging system
- 🔗 Strategic use of links and MOCs (Maps of Content)
- 📝 Ready-to-use templates for different note types
- 🚀 Easy to start, powerful to scale

## 🎯 Why Use This Template?

### Key Benefits
- **Simplicity**: Maximum two clicks to access any information
- **Efficiency**: Reduces "analysis paralysis" when deciding where to store notes
- **Flexibility**: Grows organically with your use
- **Maintenance**: Easy to maintain and reorganize when needed

## 🚀 Getting Started

1. Clone this repository or download as ZIP
2. Open Obsidian
3. Select "Open folder as vault" and choose the template folder
4. Check `99 - Meta/System/` for detailed guides on how to use the system

## 📁 Folder Structure

```
.
├── 00 - Dashboard/         # Central hub of the vault
├── 01 - Personal/          # Personal content and diary
│   ├── Daily/
│   ├── Fleeting/
│   ├── Plans/
│   ├── Reflections/
│   └── Health/
├── 02 - Knowledge/         # Study notes by area
│   ├── Computing/          # Examples of knowledge areas
│   ├── Philosophy/
│   ├── History/
│   ├── Literature/
│   └── Health/
├── 03 - Projects/          # Projects in development
│   ├── Project1/
│   ├── Project2/
│   └── Project3/
├── 04 - References/        # Source material and bibliography
│   ├── Articles/
│   ├── Courses/
│   ├── Books/
│   └── Tutorials/
└── 99 - Meta/              # System and templates
    ├── Templates/
    └── System/
```

## 🏷️ Tagging System
Check the [tag guide](99%20-%20Meta/System/Guide%20to%20Tags%20and%20Links%20-%20Note%20Organization%20in%20Obsidian.md)
 for a complete list

### 1. Type Tags
Identify the nature of the note:
```
#type/task       → Tasks
#type/project    → Projects
#type/daily      → Daily notes
#type/study      → Study material
#type/idea       → Insights
#type/reflection → Reflections
#type/habits     → Routines and habits
```

### 2. Context Tags
Indicate the note's environment:
```
#context/studies     → Learning
#context/work        → Professional
#context/personal    → Personal development
#context/academic    → University
#context/hobbies     → Personal interests
```

### 3. Theme Tags
Organize by knowledge area:
```
Computing:
#theme/cybersecurity → Security
#theme/dev           → Development
#theme/os            → Operating systems
#theme/algorithms    → Algorithms and structures
#theme/AI            → Artificial intelligence

...and much more (see complete tag guide)
```

### 4. Metadata Tags
Control status and priority:
```
#status/[completed|in-progress|planning|idea]
#priority/[high|medium|low]
#review/[pending|completed|needed]
```

### Tag Usage Best Practices

#### Required Minimum Tags
To maintain consistency and facilitate search, each note should include at minimum:
1. One type tag (`#type/...`)
2. One context tag (`#context/...`)
3. One theme tag (`#theme/...`)
4. One status/priority tag when applicable

## 🔗 Linking System

### Link Types
1. **Direct Links**: `[[Note Name]]`
2. **Alias Links**: `[[Note Name|Displayed Text]]`
3. **Section Links**: `[[Note Name#Section]]`

### Recommended Practices
- Create meaningful connections
- Use MOCs (Maps of Content) to organize themes
- Leverage backlinks to discover relationships
- Build flexible hierarchies through links

## 📚 Integrated Methods

The system incorporates practices from:
- **Zettelkasten**: Interconnected atomic notes
- **PARA**: Projects, Areas, Resources, Archives
- **Building a Second Brain**: Knowledge capture and organization
- **GTD**: Getting Things Done for task management
- **Feynman Technique**: Teaching to learn
- **Interrogative Elaboration**: Question-based learning
- **Cornell Method**: Systematic note-taking and review

## ⚙️ Recommended Plugins

### Essential:
- Iconize
- Homepage
- Dataview
- Calendar
- Backlinks
- Templates
- Daily Notes

### Optional:
- Tag Wrangler
- Graph Analysis
- Natural Language Dates
- Mind Map
- Kanban
- Templater
- Outliner

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Create Issues with suggestions
2. Submit Pull Requests with improvements
3. Share your experiences using the template
4. Report bugs or problems

## 📝 License

This project is under the MIT license. See the [LICENSE](LICENSE) file for more details.

## 🙏 Acknowledgments

This template was inspired by various knowledge management systems and the Obsidian community. Special thanks to:
- Zettelkasten Methodology
- Tiago Forte's PARA System
- r/Obsidian community
