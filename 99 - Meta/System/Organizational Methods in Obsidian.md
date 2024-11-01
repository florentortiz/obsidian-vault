---
aliases:
  - Organization in Obsidian
  - Study Methods
tags:
  - context/studies
  - type/study
  - theme/organization
  - theme/productivity
  - status/in-progress
date: 2024-10-20
last_updated: 2024-10-21
---

# Organizational Methods in Obsidian

## Introduction

This note describes the main organizational methods that can be implemented in Obsidian to improve knowledge management, studies, and projects. They include **Zettelkasten**, the **Cornell Method**, the **Pareto Principle (80/20)**, **Spaced Repetition**, **Kanban**, **Elaborative Interrogation**, the **Pomodoro Technique**, and the **Feynman Technique**. Here, we describe how to apply each of these methods to your notes and routine management.

---

## 1. Zettelkasten (Card Method)

**Concept**: Each note should be an "atomic note," containing a single idea. Connecting these notes through internal links builds a network of knowledge.

### How to apply in Obsidian:
- **Atomic Notes**: Create smaller, more focused notes. Each note should address only one concept.
- **Internal Links**: Connect related notes through `[[Note_Name]]` to create a web of interconnected ideas.
- **MOC (Map of Content)**: Create MOC notes for larger topics, listing links to smaller notes about subtopics.
- **Tags**: Classify notes with [[How to classify notes with tags|Tags in Obsidian]]

#### Example:
```markdown
# MOC - Cybersecurity
## Subtopics:
- [[Cryptography]]
- [[Firewall]]
- [[DDoS Attacks]]
```

---

## 2. Cornell Method for Study Notes

**Concept**: Organizes notes into three parts: main notes, key points, and a final summary.

### How to apply in Obsidian:
- **Main Notes**: Where you place discussed or learned topics.
- **Key Points**: Main highlights or relevant questions.
- **Final Summary**: Conclusion or synthesis of what was learned.

#### Example Structure:
```markdown
# Study of [Topic]

## Main Notes:
- Concept 1
- Concept 2

## Key Points:
- Insight 1
- Insight 2

## Summary:
- Summary of what I learned.
```

---

## 3. Pareto Principle (80/20)

**Concept**: 80% of results come from 20% of efforts. Apply this by identifying the most important notes and reorganizing them for easy access.

### How to apply in Obsidian:
- **Note Priority**: Mark the most important notes with tags like `#priority/high` and organize them for easy access.
- **Reorganization**: Create a "Key Notes" section or use Obsidian's favorites panel for quick access.

#### Example:
```markdown
# MOC - Important Notes
- [[Information Security]]
- [[C++ Optimization]]
```

---

## 4. Spaced Repetition Method

**Concept**: Reviewing information at increasing intervals helps with long-term retention.

### How to apply in Obsidian:
- **Spaced Repetition Plugin**: Use the Obsidian Spaced Repetition plugin to set automatic review reminders.
- **Review Tags**: Add the `#type/review` tag to notes that need reviewing.

#### Example:
```markdown
tags:
  - type/review
  - theme/algorithms
review_date: {{date}}
```

---

## 5. Kanban (Task Boards)

**Concept**: A visual method for tracking project progress. Ideal for dividing tasks and monitoring workflow.

### How to apply in Obsidian:
- **Obsidian Kanban Plugin**: Use the plugin to create Kanban boards and visualize tasks. Create columns for project phases and move tasks according to progress.
- **Project Management**: Ideal for managing game development stages or other personal projects.

#### Example:
```markdown
# Kanban - Game Development
- **Concept**:
  - [ ] Create basic narrative
  - [ ] Define core mechanics
- **Design**:
  - [ ] UI prototype
  - [ ] Character modeling
```

---

## 6. Elaborative Interrogation

**Concept**: Asking in-depth questions about the content helps with understanding and memorization.

### How to apply in Obsidian:
- **Questions in Notes**: Add a questions section in your study notes, especially about complex topics.
- **Reflection**: Ask questions that lead to deeper reflection on the content.

#### Example:
```markdown
## Questions:
- How can the concept of Amor Fati be applied to daily challenges?
- How does this influence my decisions under pressure?
```

---

## 7. Pomodoro Technique

**Concept**: Divide study time into 25-minute focus blocks, followed by a short 5-minute break. After four cycles, take a longer break.

#### Variation considering ultradian cycles
60-90 min of focus for 15-20 min rest (Ultradian cycles)

### How to apply in Obsidian:
- **Task List**: Create a task list for the focus block and add time reminders.
- **Timer**: Use a plugin or external application to control Pomodoro cycle times.

#### Example:
```markdown
# Pomodoro Tasks
- [ ] Study data structures - 1 cycle
- [ ] Review C++ concepts - 2 cycles
- [ ] Research network security - 3 cycles
```

---

## 8. Feynman Technique

**Concept**: Teach what you're learning to someone as if it were simple. This helps identify gaps in understanding and consolidate knowledge.

### How to apply in Obsidian:
- **Explanatory Notes**: Write explanations about the content as if you were teaching someone without prior knowledge.
- **Review**: Always review your explanations to verify clarity and knowledge gaps.

#### Example:
```markdown
# Explaining Network Security

Network security is like protecting a house, but instead of windows and doors, you have firewalls and encryption...
```

---

## Conclusion

These methods are powerful organizational tools that can be applied together in Obsidian, making your "second brain" more efficient and dynamic. Choose the methods that best adapt to your routine and adjust as needed. The combination of these practices will enhance your organization and information retention.