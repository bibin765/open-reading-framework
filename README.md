
# Open Reading Framework

A systematic approach to reading books that helps people divide books into manageable sections, set reading goals, and track their progress through structured study guides.

## Purpose

This open-source project provides structured reading frameworks for both fiction and non-fiction books. Each book is broken down into digestible sections with clear goals, timelines, and discussion prompts to enhance comprehension and retention.

## Usage

1. Browse the `fiction/` or `nonfiction/` directories to find a book you're interested in reading
2. Each book folder contains four key files:
   - `SUMMARY.md` - Overview of themes and key concepts
   - `GOALS.md` - Structured reading goals and checkpoints  
   - `TIMELINE.md` - Chapter-by-chapter reading schedule
   - `DISCUSSION.md` - Reflection questions and discussion prompts
3. Follow the suggested timeline and use the discussion questions to deepen your understanding

## Folder Structure

Each book has its own folder with structured subfolders organized by genre:

```
├── fiction/
│   ├── [Book-Title-Author]/
│   │   ├── SUMMARY.md
│   │   ├── GOALS.md  
│   │   ├── TIMELINE.md
│   │   └── DISCUSSION.md
├── nonfiction/
│   ├── [Book-Title-Author]/
│   │   ├── SUMMARY.md
│   │   ├── GOALS.md
│   │   ├── TIMELINE.md  
│   │   └── DISCUSSION.md
└── templates/
    ├── SUMMARY_TEMPLATE.md
    ├── GOALS_TEMPLATE.md
    ├── TIMELINE_TEMPLATE.md
    └── DISCUSSION_TEMPLATE.md
```

## Contributing

We welcome contributions! To add a new book:

1. Create a new folder under `fiction/` or `nonfiction/` following the naming convention `Book-Title-Author`
2. Use the templates in the `templates/` folder as a starting point
3. Fill in the four required files with meaningful content
4. Submit a pull request

Please ensure your contributions are well-researched and provide genuine value to readers looking to engage more deeply with the material. 

