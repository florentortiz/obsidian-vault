---
aliases:
  - Vault Guidelines
  - Vault Directives
tags:
  - context/studies
  - type/study
  - theme/organization
  - theme/productivity
  - status/completed
date: 2024-10-20
last_updated: 2024-10-29
---

## **Practical Usage Guide**

### **1. Creating New Notes**

#### **Decision Process**
1. Identify the main note type (task, study, reflection, etc.)
2. Choose the appropriate main folder:
   - Personal knowledge → 02 - Knowledge
   - Reflections/diary → 01 - Personal
   - Source material → 04 - References
   - Active projects → 03 - Projects

#### **Naming Convention**
- Use descriptive and concise names
- Avoid special characters
- Examples:
  - `Introduction to Algorithms`
  - `2024-01-01 Daily Reflection`
  - `Project Game Engine`

### **2. Using Tags Effectively**
For more detailed examples of tag usage, check [[How to classify notes with tags|Tag Organization System]]

#### **Recommended Tag Structure**
Always include at minimum:
1. One type tag (`#type/...`)
2. One context tag (`#context/...`)
3. One theme tag (`#theme/...`)
4. One status/priority tag when applicable

Example:
```markdown
tags:
  - type/study
  - context/academic
  - theme/algorithms
  - status/in-progress
  - priority/high
```

### **3. Creating Connections**

#### **Effective Links**
- Use bidirectional links (`[[]]`) to connect related concepts
- Create MOCs (Maps of Content) for main themes
- MOC Example:
```markdown
# MOC - Algorithms
## Fundamentals
- [[Algorithm Complexity]]
- [[Basic Data Structures]]

## Specific Algorithms
- [[Sorting Algorithms]]
- [[Search Algorithms]]
```

### **4. Daily Workflow**

#### **Recommended Routine**
1. **Start of Day**
   - Review notes with `#review/pending`
   - Update project status
   - Create daily note if needed

2. **During the Day**
   - Use fleeting notes for quick capture
   - Process fleeting notes regularly
   - Update status and tags as needed

3. **End of Day**
   - Review created notes
   - Check necessary connections
   - Plan future reviews

### **5. System Maintenance**

#### **Weekly Review**
1. Process all fleeting notes
2. Update project status
3. Check pending tags
4. Plan next week's reviews

#### **Monthly Review**
1. Archive completed projects
2. Update main MOCs
3. Check tag consistency
4. Identify areas for expansion/improvement

### **6. Common Problems and Solutions**

#### **When Unsure Where to Put a Note**
1. Consider the note's main use
2. Use tags for multiple categories
3. Create links to related contexts
4. If still unsure, use the most generic folder and specific tags

#### **When a Note Grows Too Large**
1. Split into smaller, more specific notes
2. Create a MOC note to connect them
3. Keep only the summary in the original note
4. Use links to detailed notes

### **7. Productivity Tips**

#### **Recommended Shortcuts**
- Configure template hotkeys
- Create shortcuts for common tags
- Use quick switcher for navigation

#### **Essential Plugins**
- Calendar for temporal view
- Dataview for queries
- Kanban for projects
- Graph View for visualizing connections

### **8. Usage Examples**

#### **Study Note**
```markdown
---
aliases: [Sorting Algorithms]
tags:
  - type/study
  - context/academic
  - theme/algorithms
  - status/in-progress
date: 2024-01-01
---

# Sorting Algorithms

## Objective
Understanding main sorting algorithms and their complexities.

## Content
1. Bubble Sort
2. Quick Sort
3. Merge Sort

## Connections
- [[Algorithm Complexity]]
- [[Data Structures]]

## Notes
[Content...]
```

#### **Project Note**
```markdown
---
aliases: [Project: Game Engine]
tags:
  - type/project
  - context/work
  - theme/dev
  - status/planning
date: 2024-01-01
---

# Project: Game Engine

## Objective
Create basic 2D game engine.

## Stages
1. [ ] Basic setup
2. [ ] Rendering system
3. [ ] Physics system

## Required Resources
- C++
- OpenGL

## Connections
- [[Game Development]]
- [[OpenGL Basics]]
```

## **Conclusion**

This system is designed to grow organically with use. The key is maintaining consistency in applying basic principles while allowing enough flexibility for adaptation to individual needs. Start with the basic structures and expand as needed, always keeping focus on simplicity and usability.