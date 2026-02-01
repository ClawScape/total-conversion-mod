# Contributing to Total Conversion Mod

Thank you for your interest in contributing to this project! This document outlines the process and guidelines for contributing.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Contribution Types](#contribution-types)
3. [Workflow](#workflow)
4. [Style Guidelines](#style-guidelines)
5. [Review Process](#review-process)

## Getting Started

### Prerequisites

1. Read the project README
2. Review the current phase documentation in `/docs/`
3. Check the task list in `/planning/TASKS.md`
4. Familiarize yourself with the templates in `/docs/templates/`

### Claiming a Task

1. Browse open issues or `/planning/TASKS.md`
2. Comment on the issue to claim it
3. Wait for assignment confirmation
4. Create a branch for your work

## Contribution Types

### Writing Contributions

- Lore documents
- Dialogue scripts
- Descriptions
- Quest text

**Guidelines:**
- Follow established tone and style
- Check for consistency with existing lore
- Use proper grammar and spelling
- Include all required sections from templates

### Design Contributions

- Game system designs
- Region/city/dungeon layouts
- Character designs
- Balance spreadsheets

**Guidelines:**
- Use the appropriate template
- Consider gameplay implications
- Document reasoning for decisions
- Include visual references when helpful

### Art Contributions

- Concept art
- Mood boards
- Reference collections
- Asset designs

**Guidelines:**
- Match established art direction
- Include source/license information for references
- Use consistent file formats
- Follow naming conventions

### Documentation Contributions

- Technical documentation
- Process documentation
- Guides and tutorials

**Guidelines:**
- Keep documentation up to date
- Use clear, concise language
- Include examples where helpful
- Follow markdown formatting standards

## Workflow

### Branch Naming

Use the following format:
```
<type>/<phase>/<brief-description>
```

Examples:
- `design/phase1/faction-iron-legion`
- `writing/phase1/region-shadowfen-lore`
- `docs/phase0/setup-guide`

Types:
- `design` - Game design documents
- `writing` - Lore, dialogue, descriptions
- `art` - Art assets and references
- `docs` - Documentation
- `fix` - Corrections and fixes

### Commit Messages

Use clear, descriptive commit messages:

```
<type>: <brief description>

[optional body with more details]

[optional footer with issue references]
```

Examples:
- `design: Add Iron Legion faction document`
- `writing: Complete Shadowfen region lore`
- `fix: Correct faction relationship inconsistency`

### Pull Requests

1. Create a PR using the template
2. Link related issues
3. Ensure all checklist items are complete
4. Request review from appropriate team members
5. Address feedback promptly

## Style Guidelines

### Markdown

- Use ATX-style headers (`#`, `##`, `###`)
- Use fenced code blocks with language specification
- Use tables for structured data
- Include alt text for images

### Design Documents

- Use the provided templates
- Fill out all required sections
- Mark optional sections as N/A if not applicable
- Include visual references when available

### Writing

- Use consistent tense (present for current state, past for history)
- Maintain established tone for the world
- Use proper nouns consistently
- Avoid real-world references unless intentional

### File Organization

```
docs/
├── phase0/           # Foundation docs
├── phase1/           # World design docs
│   ├── factions/     # Faction documents
│   ├── regions/      # Region documents
│   ├── cities/       # City/town documents
│   └── dungeons/     # Dungeon documents
├── phase2/           # Character design docs
│   ├── player/       # Player character docs
│   ├── npcs/         # NPC documents
│   ├── monsters/     # Monster documents
│   └── bosses/       # Boss documents
└── templates/        # Document templates
```

### Naming Conventions

**Files:**
- Use lowercase with hyphens: `iron-legion.md`
- Include type prefix when helpful: `faction-iron-legion.md`

**Folders:**
- Use lowercase with hyphens
- Group by category, then by specific item

## Review Process

### Who Reviews What

| Contribution Type | Primary Reviewer | Secondary |
|-------------------|------------------|-----------|
| Lore/Writing | Lore Lead | Design Lead |
| Game Design | Design Lead | Tech Lead |
| Art Direction | Art Lead | Design Lead |
| Documentation | Tech Lead | Any Lead |

### Review Criteria

1. **Completeness** - All required sections filled
2. **Consistency** - Matches existing content
3. **Quality** - Well-written and thought out
4. **Feasibility** - Can be implemented
5. **Balance** - Fits within game systems

### Feedback

- Be constructive and specific
- Suggest solutions, not just problems
- Approve when criteria are met
- Request changes clearly

## Questions?

If you have questions:
1. Check existing documentation
2. Search closed issues
3. Ask in discussions
4. Create an issue if needed

Thank you for contributing!
