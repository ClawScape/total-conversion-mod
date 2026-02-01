# Quick Start Guide

## First Steps

### 1. Review Project Structure

```
total-conversion-mod/
├── docs/
│   ├── phase0/          # Foundation documentation
│   ├── phase1/          # World design documentation
│   ├── phase2/          # Character design documentation
│   └── templates/       # Document templates
├── planning/
│   ├── TASKS.md         # Complete task list
│   ├── MILESTONES.md    # Project milestones
│   ├── LABELS.md        # Label definitions
│   └── QUICKSTART.md    # This file
├── content/             # Game content files (future)
├── assets/              # Art, music assets (future)
├── .github/             # GitHub templates
├── README.md            # Project overview
└── CONTRIBUTING.md      # Contribution guidelines
```

### 2. Understand the Phases

| Phase | Focus | Tasks |
|-------|-------|-------|
| 0 | Foundation | ~250 |
| 1 | World Design | ~900 |
| 2 | Character Design | ~800 |

### 3. Check Current Phase

Look at `planning/TASKS.md` to see:
- Which tasks are completed `[x]`
- Which are in progress `[~]`
- Which are pending `[ ]`

## Working on Tasks

### Finding Tasks

1. Open `planning/TASKS.md`
2. Find tasks with `[ ]` (not started)
3. Check for `priority:critical` tasks first
4. Look for tasks without blockers

### Claiming a Task

1. Create a GitHub issue for the task
2. Assign yourself
3. Create a branch

### Completing a Task

1. Use the appropriate template from `docs/templates/`
2. Create your document in the correct folder
3. Update `TASKS.md` to mark as complete `[x]`
4. Submit a pull request

## Templates

| Template | Use For |
|----------|---------|
| `FACTION_TEMPLATE.md` | Faction design |
| `REGION_TEMPLATE.md` | Region design |
| `CITY_TEMPLATE.md` | City/town design |
| `DUNGEON_TEMPLATE.md` | Dungeon design |
| `NPC_TEMPLATE.md` | NPC profiles |
| `MONSTER_TEMPLATE.md` | Monster design |
| `BOSS_TEMPLATE.md` | Boss encounters |

## Priority Order

### Phase 0 Critical Path

1. GitHub setup (0.1.1-0.1.5)
2. Development environment (0.2.1-0.2.5)
3. Play original game (0.3.1)
4. Core design decisions (0.4.1-0.4.5)

### Phase 1 Critical Path

1. Creation myth (1.1.1.1)
2. World overview (1.1.2.1-1.1.2.3)
3. World map sketch (1.2.1.1)
4. Starting region (1.3.1)
5. Tutorial dungeon (1.5.1)

### Phase 2 Critical Path

1. Race decision (2.1.1.1)
2. Player character art (2.1.6.1-2.1.6.2)
3. Monster system design (2.3.1)
4. Starter monsters (2.3.3.1)
5. Tutorial boss (2.4.2.1)

## Tips

1. **Start with Phase 0** - Foundation work enables everything else
2. **Follow the templates** - Consistency matters
3. **Check dependencies** - Some tasks block others
4. **Ask questions** - Use GitHub discussions
5. **Small PRs** - Easier to review

## Getting Help

- Check `docs/` for documentation
- Review existing completed tasks for examples
- Create a discussion for questions
- Tag relevant team members in issues
