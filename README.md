# Quarry Templates

Official template collection for [Quarry Codex](https://framers.dev) - a modern personal knowledge management system.

## Overview

This repository contains 50+ templates for creating structured notes, documentation, and content in Quarry Codex. Templates are automatically synced to the app and available in the template selector.

## Categories

| Category | Description | Templates |
|----------|-------------|-----------|
| General | Universal templates for any content | Blank, Quick Note, Checklist, Todo List, Project Tracker, Collection |
| Technical | Documentation and reference materials | Concept, Tutorial, Reference, Troubleshooting, Architecture, Changelog |
| Creative | Writing and artistic projects | Story Outline, Character Profile, World Building, Book Review, Poetry |
| Personal | Self-improvement and journaling | Journal, Goal Setting, Gratitude, Life Lesson, Habit Tracker, Reflection |
| Business | Professional documentation | Meeting Notes, Project Plan, Case Study, Proposal, Retrospective |
| Learning | Study materials and education | Study Notes, Book Summary, Research Notes, Course Outline, Flashcards |
| Lifestyle | Health, travel, and daily life | Recipe, Workout, Travel Itinerary, Event Plan, Meal Plan |
| Research | Academic and investigative docs | Literature Review, Experiment, Interview, Data Analysis, Thesis |

## Usage

Templates are automatically available in Quarry Codex. To use a template:

1. Open Quarry Codex
2. Click "New Strand" or press `Cmd/Ctrl + N`
3. Select a template from the template selector
4. Fill in the form fields
5. Start writing!

## Template Structure

Each template is a JSON file with the following structure:

```json
{
  "id": "unique-id",
  "name": "Template Name",
  "category": "general",
  "icon": "FileText",
  "description": "Full description",
  "shortDescription": "Short desc",
  "difficulty": "beginner",
  "estimatedTime": "5 min",
  "tags": ["tag1", "tag2"],
  "version": "1.0.0",
  "author": "Framers AI",
  "featured": false,
  "popularity": 50,
  "defaultData": {},
  "fields": [],
  "template": "# {{title}}\n\nContent here..."
}
```

## Contributing

Want to add a template?

1. Fork this repository
2. Create your template JSON in the appropriate category folder
3. Add the template entry to `registry.json`
4. Submit a pull request

## License

MIT License - See [LICENSE](LICENSE) for details.

---

Built with love by [Framers AI](https://framers.dev)
