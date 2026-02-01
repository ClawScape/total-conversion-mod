# Total Conversion Mod - Label Reference

## Phase Labels

| Label | Color | Description |
|-------|-------|-------------|
| `phase:foundation` | `#0E8A16` | Phase 0 - Foundation tasks |
| `phase:world` | `#1D76DB` | Phase 1 - World Design tasks |
| `phase:characters` | `#5319E7` | Phase 2 - Character Design tasks |

## Type Labels

| Label | Color | Description |
|-------|-------|-------------|
| `type:writing` | `#FBCA04` | Lore, dialogue, descriptions, documentation |
| `type:design` | `#F9D0C4` | Game design, system design, UI design |
| `type:art` | `#E99695` | Visual art, models, animations |
| `type:music` | `#C2E0C6` | Music, sound effects, audio |
| `type:documentation` | `#BFD4F2` | Technical documentation, guides |
| `type:infrastructure` | `#D4C5F9` | Project setup, tools, CI/CD |

## Priority Labels

| Label | Color | Description |
|-------|-------|-------------|
| `priority:critical` | `#B60205` | Must complete first, blocks other work |
| `priority:high` | `#D93F0B` | Important, should complete soon |
| `priority:medium` | `#FBCA04` | Standard priority |
| `priority:low` | `#0E8A16` | Can be deferred |

## Status Labels

| Label | Color | Description |
|-------|-------|-------------|
| `status:blocked` | `#B60205` | Blocked by dependency |
| `status:review` | `#FBCA04` | Ready for review |
| `status:approved` | `#0E8A16` | Approved and ready |
| `status:wip` | `#1D76DB` | Work in progress |

## Component Labels

| Label | Color | Description |
|-------|-------|-------------|
| `component:engine` | `#006B75` | Engine/server related |
| `component:client` | `#0052CC` | Client related |
| `component:content` | `#5319E7` | Content/assets related |
| `component:tools` | `#BFD4F2` | Development tools |

## Category Labels

| Label | Color | Description |
|-------|-------|-------------|
| `category:lore` | `#C5DEF5` | World lore and history |
| `category:faction` | `#D4C5F9` | Faction related |
| `category:region` | `#BFDADC` | Region design |
| `category:city` | `#FEF2C0` | City/town design |
| `category:dungeon` | `#E99695` | Dungeon design |
| `category:npc` | `#C2E0C6` | NPC design |
| `category:monster` | `#F9D0C4` | Monster design |
| `category:boss` | `#B60205` | Boss design |
| `category:player` | `#0E8A16` | Player character |

## GitHub Label Setup Script

```bash
#!/bin/bash
# Run this in your repository to create all labels

# Phase labels
gh label create "phase:foundation" --color "0E8A16" --description "Phase 0 - Foundation"
gh label create "phase:world" --color "1D76DB" --description "Phase 1 - World Design"
gh label create "phase:characters" --color "5319E7" --description "Phase 2 - Character Design"

# Type labels
gh label create "type:writing" --color "FBCA04" --description "Lore, dialogue, descriptions"
gh label create "type:design" --color "F9D0C4" --description "Game/system design"
gh label create "type:art" --color "E99695" --description "Visual art, models, animations"
gh label create "type:music" --color "C2E0C6" --description "Music, sound effects"
gh label create "type:documentation" --color "BFD4F2" --description "Technical documentation"
gh label create "type:infrastructure" --color "D4C5F9" --description "Project setup, tools"

# Priority labels
gh label create "priority:critical" --color "B60205" --description "Must complete first"
gh label create "priority:high" --color "D93F0B" --description "Important"
gh label create "priority:medium" --color "FBCA04" --description "Standard priority"
gh label create "priority:low" --color "0E8A16" --description "Can be deferred"

# Status labels
gh label create "status:blocked" --color "B60205" --description "Blocked by dependency"
gh label create "status:review" --color "FBCA04" --description "Ready for review"
gh label create "status:approved" --color "0E8A16" --description "Approved and ready"
gh label create "status:wip" --color "1D76DB" --description "Work in progress"

# Component labels
gh label create "component:engine" --color "006B75" --description "Engine/server related"
gh label create "component:client" --color "0052CC" --description "Client related"
gh label create "component:content" --color "5319E7" --description "Content/assets related"
gh label create "component:tools" --color "BFD4F2" --description "Development tools"
```
