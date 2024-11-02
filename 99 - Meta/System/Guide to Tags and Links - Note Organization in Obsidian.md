---
aliases:
  - Tags and Links in Obsidian
  - Organization System
tags:
  - context/studies
  - type/study
  - theme/organization
  - theme/productivity
  - status/completed
date: 2024-10-30
---

# **Guide to Tags and Links - Note Organization in Obsidian**

## **1. Note Type Tags**
Identify the primary nature of the note, helping with basic content categorization.

### Examples:
- `#type/task` → To-do items
- `#type/project` → Projects in development
- `#type/daily` → Daily notes
- `#type/study` → Learning material
- `#type/idea` → Insights and brainstorming
- `#type/reflection` → Personal thoughts and analysis
- `#type/habits` → Routines and habits

## **2. Context Tags**
Indicate the environment or circumstance where the note applies.

### Examples:
- `#context/studies` → General learning material
- `#context/work` → Professional activities
- `#context/personal` → Personal development
- `#context/academic` → University studies
- `#context/hobbies` → Recreational activities

## **3. Theme Tags**
Organize content by area of knowledge or interest.

### Computing and Technology
- `#theme/cybersecurity` → Information security
- `#theme/dev` → Software development
- `#theme/os` → Operating systems
- `#theme/algorithms` → Algorithms and data structures
- `#theme/AI` → Artificial intelligence

### Humanities
- `#theme/psychology` → Human behavior
- `#theme/stoicism` → Stoic philosophy
- `#theme/history` → Historical studies
- `#theme/mythology` → Mythological studies

### Health and Wellness
- `#theme/muay-thai` → Martial arts
- `#theme/fitness` → Exercise and nutrition

### Culture and Entertainment
- `#theme/music` → Musical studies
- `#theme/movies` → Cinema and series
- `#theme/drawing` → Visual arts
- `#theme/games` → Games and game dev
- `#theme/literature` → Books and reading

## **4. Metadata Tags**
Control notes' status, priority, and review needs.

### Status and Progress
- `#status/completed` → Finished
- `#status/in-progress` → Under development
- `#status/planning` → Initial phase
- `#status/idea` → Initial concept

### Prioritization
- `#priority/high` → Urgent
- `#priority/medium` → Important
- `#priority/low` → Can wait

### Review Control
- `#review/pending` → Awaiting review
- `#review/completed` → Already reviewed
- `#review/needed` → Needs review

## 5. Tag Usage Best Practices

#### Required Minimum Tags
To maintain consistency and facilitate search, each note should include at minimum:
1. One type tag (`#type/...`)
2. One context tag (`#context/...`)
3. One theme tag (`#theme/...`)
4. One status/priority tag when applicable

## **6. Using Links**
Links are fundamental for creating connections between notes, forming an interconnected knowledge network.

### Link Types

1. **Direct Links**
   - Syntax: `[[Note Name]]`
   - Usage: Directly connects to another note
   - Example: `[[Cryptography Algorithms]]`

2. **Alias Links**
   - Syntax: `[[Note Name|Displayed Text]]`
   - Usage: Shows different text from the note title
   - Example: `[[Cryptography Algorithms|Encryption Methods]]`

3. **Section Links**
   - Syntax: `[[Note Name#Section]]`
   - Usage: Takes you to a specific section of a note
   - Example: `[[Cryptography#RSA]]`

### Recommended Link Practices

1. **Meaningful Connections**
   - Create links only when there's a relevant relationship
   - Avoid excessive links that might distract

2. **Index Notes (MOCs)**
   - Create notes that serve as maps of content
   - Use links to organize related themes
   - Example: A "[[Security Projects]]" note with links to all related projects

3. **Bidirectional Links**
   - Take advantage of Obsidian's automatic backlinks
   - Periodically review backlinks to discover new connections

4. **Hierarchy through Links**
   - Use links to create flexible hierarchical structures
   - Example: `[[Programming]]` → `[[Algorithms]]` → `[[Sorting]]`

## **7. Complete Usage Example**

### Title: **RSA Implementation**
**Tags**: 
- `#theme/cybersecurity`
- `#context/studies`
- `#type/study`
- `#priority/high`
- `#status/in-progress`
- `#review/pending`

**Related Links**:
- [[Asymmetric Cryptography]]
- [[Security Projects]]
- [[Cryptography Mathematics#Prime Numbers]]

**Content**:
Details about RSA implementation, with references to fundamental concepts through links.
