# ClawScape - Atomic Task List

> **Task Status:** `[ ]` Available | `[~]` In Progress | `[x]` Complete | `[B]` Blocked
>
> **Commit Format:** `complete: [TASK-ID] Brief description`
>
> **Rule:** One task = One commit. No scope creep.

---

# PHASE 0: FOUNDATION

## 0.1 Project Infrastructure

### 0.1.1 GitHub Organization 🔀 PARALLEL
- [ ] `P0.1.1.1` Create ClawScape GitHub organization
- [ ] `P0.1.1.2` Set up organization profile and description
- [ ] `P0.1.1.3` Configure organization settings
- [ ] `P0.1.1.4` Set up organization security policies

### 0.1.2 Repository Structure
- [B] `P0.1.2.1` Fork lostcity (2004scape/Server) to ClawScape org
  - Blocked by: P0.1.1.1
- [B] `P0.1.2.2` Transfer total-conversion-mod to ClawScape org
  - Blocked by: P0.1.1.1
- [B] `P0.1.2.3` Configure branch protection rules
  - Blocked by: P0.1.2.1, P0.1.2.2
- [B] `P0.1.2.4` Set up repository templates
  - Blocked by: P0.1.2.1, P0.1.2.2

### 0.1.3 GitHub Project Board
- [B] `P0.1.3.1` Create GitHub Project board
  - Blocked by: P0.1.1.1
- [B] `P0.1.3.2` Configure custom fields (Phase, Type, Priority)
  - Blocked by: P0.1.3.1
- [B] `P0.1.3.3` Set up project views (Kanban, Roadmap)
  - Blocked by: P0.1.3.1
- [B] `P0.1.3.4` Link repositories to project
  - Blocked by: P0.1.3.1, P0.1.2.1, P0.1.2.2

### 0.1.4 Issue & PR Templates 🔀 PARALLEL
- [ ] `P0.1.4.1` Create bug report template
- [ ] `P0.1.4.2` Create feature request template
- [ ] `P0.1.4.3` Create task template
- [ ] `P0.1.4.4` Create design document template
- [ ] `P0.1.4.5` Create pull request template

### 0.1.5 Labels Setup
- [B] `P0.1.5.1` Create and sync all labels across repos
  - Blocked by: P0.1.2.1, P0.1.2.2
  - See planning/LABELS.md for label definitions

---

## 0.2 Development Environment

### 0.2.1 Prerequisites Documentation 🔀 PARALLEL
- [ ] `P0.2.1.1` Document required software versions
- [ ] `P0.2.1.2` Document hardware requirements
- [ ] `P0.2.1.3` Create Windows setup guide
- [ ] `P0.2.1.4` Create macOS setup guide
- [ ] `P0.2.1.5` Create Linux setup guide

### 0.2.2 Local Development Setup
- [B] `P0.2.2.1` Create setup script for lostcity server
  - Blocked by: P0.1.2.1
- [B] `P0.2.2.2` Create setup script for lostcity client
  - Blocked by: P0.1.2.1
- [B] `P0.2.2.3` Document database setup
  - Blocked by: P0.2.2.1
- [B] `P0.2.2.4` Document local server configuration
  - Blocked by: P0.2.2.1
- [B] `P0.2.2.5` Create environment variable template
  - Blocked by: P0.2.2.1

### 0.2.3 Development Tools 🔀 PARALLEL
- [ ] `P0.2.3.1` Configure linter settings
- [ ] `P0.2.3.2` Configure formatter settings
- [ ] `P0.2.3.3` Set up pre-commit hooks
- [ ] `P0.2.3.4` Configure debug configurations
- [ ] `P0.2.3.5` Set up test runners

### 0.2.4 Development Workflow Documentation 🔀 PARALLEL
- [ ] `P0.2.4.1` Document branching strategy
- [ ] `P0.2.4.2` Document commit message conventions
- [ ] `P0.2.4.3` Document code review process
- [ ] `P0.2.4.4` Document release process
- [ ] `P0.2.4.5` Create contribution guidelines

### 0.2.5 Docker Environment
- [B] `P0.2.5.1` Create Dockerfile for server
  - Blocked by: P0.2.2.1
- [B] `P0.2.5.2` Create docker-compose.yml
  - Blocked by: P0.2.5.1
- [B] `P0.2.5.3` Document Docker usage
  - Blocked by: P0.2.5.2

---

## 0.3 Codebase Understanding

### 0.3.1 Play Original Game
- [B] `P0.3.1.1` Set up and run lostcity locally
  - Blocked by: P0.2.2.1
- [B] `P0.3.1.2` Complete tutorial area
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.3` Reach level 20 in any skill
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.4` Complete 5 quests
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.5` Explore 10 different regions
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.6` Test combat system thoroughly
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.7` Test crafting/skilling systems
  - Blocked by: P0.3.1.1
- [B] `P0.3.1.8` Document gameplay observations
  - Blocked by: P0.3.1.2-7

### 0.3.2 Engine Analysis - Core 🔀 PARALLEL
- [B] `P0.3.2.1` Document app.ts / application lifecycle
  - Blocked by: P0.3.1.1
- [B] `P0.3.2.2` Document World.ts / world management
  - Blocked by: P0.3.1.1
- [B] `P0.3.2.3` Document entity system architecture
  - Blocked by: P0.3.1.1
- [B] `P0.3.2.4` Document zone system
  - Blocked by: P0.3.1.1

### 0.3.3 Engine Analysis - Systems 🔀 PARALLEL
- [B] `P0.3.3.1` Document script execution model
  - Blocked by: P0.3.2.1
- [B] `P0.3.3.2` Document network protocol
  - Blocked by: P0.3.2.1
- [B] `P0.3.3.3` Document database schema
  - Blocked by: P0.3.2.1
- [B] `P0.3.3.4` Document configuration system
  - Blocked by: P0.3.2.1

### 0.3.4 Client Analysis 🔀 PARALLEL
- [B] `P0.3.4.1` Document client initialization
  - Blocked by: P0.3.1.1
- [B] `P0.3.4.2` Document rendering system
  - Blocked by: P0.3.1.1
- [B] `P0.3.4.3` Document UI system
  - Blocked by: P0.3.1.1
- [B] `P0.3.4.4` Document input handling
  - Blocked by: P0.3.1.1

### 0.3.5 Content Analysis 🔀 PARALLEL
- [B] `P0.3.5.1` Document RuneScript syntax and features
  - Blocked by: P0.3.3.1
- [B] `P0.3.5.2` Document map file format
  - Blocked by: P0.3.2.4
- [B] `P0.3.5.3` Document model/animation formats
  - Blocked by: P0.3.4.2
- [B] `P0.3.5.4` Document content folder structure
  - Blocked by: P0.3.5.1

### 0.3.6 System Tracing 🔀 PARALLEL
- [B] `P0.3.6.1` Trace login flow end-to-end
  - Blocked by: P0.3.2.1-4
- [B] `P0.3.6.2` Trace dialogue system
  - Blocked by: P0.3.3.1
- [B] `P0.3.6.3` Trace combat system with formulas
  - Blocked by: P0.3.3.1
- [B] `P0.3.6.4` Trace skill/experience system
  - Blocked by: P0.3.3.1
- [B] `P0.3.6.5` Trace quest system
  - Blocked by: P0.3.3.1

---

## 0.4 Core Design Decisions

### 0.4.1 Identity Decisions
- [ ] `P0.4.1.1` Choose final game name
  - Scope: Update DESIGN_DECISIONS.md with name choice
- [ ] `P0.4.1.2` Write elevator pitch (1 paragraph)
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.1.3` Define core vision statement
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.1.4` Create tagline
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.1.5` Define target audience
  - Scope: Update DESIGN_DECISIONS.md

### 0.4.2 Setting Decisions
- [ ] `P0.4.2.1` Define setting theme (fantasy/sci-fi/etc)
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.2.2` Define technology level
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.2.3` Define magic system presence/rules
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.2.4` Define overall tone
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.2.5` Define playable races
  - Scope: Update DESIGN_DECISIONS.md

### 0.4.3 Gameplay Decisions 🔀 PARALLEL
- [ ] `P0.4.3.1` Define skill system approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.2` Define combat system approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.3` Define death/respawn mechanics
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.4` Define PvP approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.5` Define quest system approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.6` Define progression philosophy
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.3.7` Define endgame content approach
  - Scope: Update DESIGN_DECISIONS.md

### 0.4.4 Technical Decisions 🔀 PARALLEL
- [ ] `P0.4.4.1` Define target platforms
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.4.2` Define graphics quality targets
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.4.3` Define server architecture approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.4.4` Define database technology
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.4.5` Define scaling strategy
  - Scope: Update DESIGN_DECISIONS.md

### 0.4.5 Art Direction 🔀 PARALLEL
- [ ] `P0.4.5.1` Define art style
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.5.2` Define color palette approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.5.3` Define UI style
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.5.4` Create initial mood board (30-50 images)
  - Scope: Add to assets/references/, update DESIGN_DECISIONS.md

### 0.4.6 Music Direction 🔀 PARALLEL
- [ ] `P0.4.6.1` Define music style
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.6.2` Define instrument palette
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.6.3` Create reference playlist
  - Scope: Update DESIGN_DECISIONS.md with links
- [ ] `P0.4.6.4` Define sound effect style
  - Scope: Update DESIGN_DECISIONS.md

### 0.4.7 Business Decisions 🔀 PARALLEL
- [ ] `P0.4.7.1` Define monetization model
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.7.2` Define open source approach
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.7.3` Define modding support level
  - Scope: Update DESIGN_DECISIONS.md
- [ ] `P0.4.7.4` Define community guidelines
  - Scope: Update DESIGN_DECISIONS.md

---

## 0.5 Documentation Structure

- [ ] `P0.5.1.1` Set up documentation site (if needed)
  - Scope: Configure docs site generator or confirm markdown-only approach
- [ ] `P0.5.1.2` Create documentation index
  - Scope: Create docs/INDEX.md linking all docs
- [ ] `P0.5.1.3` Verify all templates are complete
  - Scope: Review docs/templates/, add missing sections

---

# PHASE 1: WORLD DESIGN

## 1.1 Lore & Setting Foundation

### 1.1.1 Creation & History
- [B] `P1.1.1.1` Write world creation myth (2-3 pages)
  - Blocked by: P0.4.2.1-4 (setting decisions)
  - Scope: Add to docs/phase1/LORE_BIBLE.md
- [B] `P1.1.1.2` Define primordial era
  - Blocked by: P1.1.1.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.3` Define ancient era
  - Blocked by: P1.1.1.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.4` Define classical era
  - Blocked by: P1.1.1.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.5` Define modern era
  - Blocked by: P1.1.1.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.6` Create world history timeline
  - Blocked by: P1.1.1.2-5
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.7` Define the current conflict
  - Blocked by: P1.1.1.5
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.1.8` Define the player's role
  - Blocked by: P1.1.1.7
  - Scope: Add to LORE_BIBLE.md

### 1.1.2 World Overview
- [B] `P1.1.2.1` Name the world
  - Blocked by: P0.4.2.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.2.2` Write world elevator pitch
  - Blocked by: P1.1.2.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.2.3` Write world overview (3-5 pages)
  - Blocked by: P1.1.1.1-8
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.2.4` Define world scale
  - Blocked by: P1.1.2.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.2.5` Define world geography basics
  - Blocked by: P1.1.2.4
  - Scope: Add to LORE_BIBLE.md

### 1.1.3 Factions 🔀 PARALLEL
- [B] `P1.1.3.0` Define total number of factions (4-6)
  - Blocked by: P1.1.1.7
  - Scope: Add to LORE_BIBLE.md

#### Faction 1-6 (all parallel after P1.1.3.0)
- [B] `P1.1.3.1` Define Faction 1 (name, overview, goals, values, territory, leadership, aesthetics, history, key NPCs)
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-1.md using template
- [B] `P1.1.3.2` Define Faction 2
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-2.md
- [B] `P1.1.3.3` Define Faction 3
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-3.md
- [B] `P1.1.3.4` Define Faction 4
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-4.md
- [B] `P1.1.3.5` Define Faction 5 (if applicable)
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-5.md
- [B] `P1.1.3.6` Define Faction 6 (if applicable)
  - Blocked by: P1.1.3.0
  - Scope: Create docs/phase1/factions/faction-6.md

### 1.1.4 Faction Relationships
- [B] `P1.1.4.1` Create faction relationship matrix
  - Blocked by: P1.1.3.1-6
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.4.2` Write all faction pair relationships (15 pairs for 6 factions)
  - Blocked by: P1.1.4.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.4.3` Define player faction mechanics
  - Blocked by: P1.1.4.1, P0.4.3.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.4.4` Define faction reputation levels and rewards
  - Blocked by: P1.1.4.3
  - Scope: Add to LORE_BIBLE.md

### 1.1.5 World Rules 🔀 PARALLEL
- [B] `P1.1.5.1` Define magic system details
  - Blocked by: P0.4.2.3
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.2` Define magic sources and limitations
  - Blocked by: P1.1.5.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.3` Define magic schools/types
  - Blocked by: P1.1.5.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.4` Define technology details
  - Blocked by: P0.4.2.2
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.5` Define tech/magic interaction
  - Blocked by: P1.1.5.1, P1.1.5.4
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.6` Define religions and deities
  - Blocked by: P1.1.1.1
  - Scope: Add to LORE_BIBLE.md
- [B] `P1.1.5.7` Define common vs forbidden knowledge
  - Blocked by: P1.1.5.6
  - Scope: Add to LORE_BIBLE.md

### 1.1.6 Visual References 🔀 PARALLEL
- [B] `P1.1.6.1` Create world mood board
  - Blocked by: P0.4.5.4
  - Scope: Add to assets/references/world/
- [B] `P1.1.6.2` Create architecture mood board
  - Blocked by: P0.4.5.4
  - Scope: Add to assets/references/architecture/
- [B] `P1.1.6.3` Create landscape mood board
  - Blocked by: P0.4.5.4
  - Scope: Add to assets/references/landscape/
- [B] `P1.1.6.4` Create character mood board
  - Blocked by: P0.4.5.4
  - Scope: Add to assets/references/characters/
- [B] `P1.1.6.5` Create faction mood boards (1 per faction)
  - Blocked by: P1.1.3.1-6
  - Scope: Add to assets/references/factions/

---

## 1.2 World Map Design

### 1.2.1 Continental Layout
- [B] `P1.2.1.1` Sketch continent rough shape
  - Blocked by: P1.1.2.5
  - Scope: Add to assets/art/maps/
- [B] `P1.2.1.2` Define world map dimensions (in tiles)
  - Blocked by: P1.2.1.1
  - Scope: Add to docs/phase1/WORLD_MAP.md
- [B] `P1.2.1.3` Place major oceans and seas
  - Blocked by: P1.2.1.1
  - Scope: Update map, add to WORLD_MAP.md
- [B] `P1.2.1.4` Place major mountain ranges
  - Blocked by: P1.2.1.1
  - Scope: Update map, add to WORLD_MAP.md
- [B] `P1.2.1.5` Place major rivers
  - Blocked by: P1.2.1.4
  - Scope: Update map, add to WORLD_MAP.md
- [B] `P1.2.1.6` Place major forests
  - Blocked by: P1.2.1.1
  - Scope: Update map, add to WORLD_MAP.md
- [B] `P1.2.1.7` Place deserts and other features
  - Blocked by: P1.2.1.1
  - Scope: Update map, add to WORLD_MAP.md
- [B] `P1.2.1.8` Create digital world map (rough)
  - Blocked by: P1.2.1.3-7
  - Scope: Add to assets/art/maps/

### 1.2.2 Biomes 🔀 PARALLEL
- [B] `P1.2.2.1` Define Temperate Forest biome (locations, climate, flora, fauna, resources)
  - Blocked by: P1.2.1.8
  - Scope: Add to docs/phase1/BIOMES.md
- [B] `P1.2.2.2` Define Desert biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.3` Define Tundra biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.4` Define Swamp biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.5` Define Volcanic biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.6` Define Coastal biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.7` Define Underground biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.8` Define Magical/Corrupted biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.9` Define Plains biome
  - Blocked by: P1.2.1.8
- [B] `P1.2.2.10` Create biome distribution map
  - Blocked by: P1.2.2.1-9
  - Scope: Add to assets/art/maps/

### 1.2.3 Region Planning
- [B] `P1.2.3.1` Define total number of regions (~13)
  - Blocked by: P1.2.1.8
  - Scope: Add to docs/phase1/REGIONS.md
- [B] `P1.2.3.2` Name all regions
  - Blocked by: P1.2.3.1
  - Scope: Add to REGIONS.md
- [B] `P1.2.3.3` Draw region boundaries on map
  - Blocked by: P1.2.3.2
  - Scope: Update map
- [B] `P1.2.3.4` Assign biomes to each region
  - Blocked by: P1.2.3.3, P1.2.2.10
  - Scope: Add to REGIONS.md
- [B] `P1.2.3.5` Assign factions to each region
  - Blocked by: P1.2.3.3, P1.1.3.1-6
  - Scope: Add to REGIONS.md
- [B] `P1.2.3.6` Assign level ranges to each region
  - Blocked by: P1.2.3.3
  - Scope: Add to REGIONS.md
- [B] `P1.2.3.7` Create region overview table
  - Blocked by: P1.2.3.4-6
  - Scope: Add to REGIONS.md

### 1.2.4 Travel & Connectivity
- [B] `P1.2.4.1` Design main road network
  - Blocked by: P1.2.3.3
  - Scope: Add to docs/phase1/TRAVEL.md
- [B] `P1.2.4.2` Design secondary paths
  - Blocked by: P1.2.4.1
- [B] `P1.2.4.3` Design sea travel routes
  - Blocked by: P1.2.1.3
- [B] `P1.2.4.4` Design fast travel system
  - Blocked by: P1.2.4.1
- [B] `P1.2.4.5` Define fast travel unlock requirements
  - Blocked by: P1.2.4.4
- [B] `P1.2.4.6` List all natural barriers
  - Blocked by: P1.2.1.4-5
- [B] `P1.2.4.7` Define gated content requirements
  - Blocked by: P1.2.3.6

---

## 1.3 Region Detail Design 🔀 PARALLEL (after P1.2.3.7)

### Region Template (15 tasks per region)
Each region document goes in `docs/phase1/regions/[region-name].md`

### Starting Region (Tutorial)
- [B] `P1.3.1.1` Complete Starting Region design document
  - Blocked by: P1.2.3.7
  - Scope: Create docs/phase1/regions/starting-region.md using REGION_TEMPLATE
  - Includes: name, description, theme, lore, map layout, cities, dungeons, POIs, resources, monsters, NPCs, quests, music, mood board, travel connections

### Regions 2-13 🔀 PARALLEL
- [B] `P1.3.2.1` Complete Region 2 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.3.1` Complete Region 3 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.4.1` Complete Region 4 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.5.1` Complete Region 5 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.6.1` Complete Region 6 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.7.1` Complete Region 7 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.8.1` Complete Region 8 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.9.1` Complete Region 9 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.10.1` Complete Region 10 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.11.1` Complete Region 11 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.12.1` Complete Region 12 design document
  - Blocked by: P1.2.3.7
- [B] `P1.3.13.1` Complete Region 13 design document
  - Blocked by: P1.2.3.7

---

## 1.4 Cities & Towns 🔀 PARALLEL (after region docs)

Each city/town document goes in `docs/phase1/cities/[city-name].md`

### Cities (10 total)
- [B] `P1.4.1.1` Complete Capital City design document
  - Blocked by: P1.3.X.1 (respective region)
  - Scope: Create using CITY_TEMPLATE
- [B] `P1.4.2.1` Complete City 2 design document
- [B] `P1.4.3.1` Complete City 3 design document
- [B] `P1.4.4.1` Complete City 4 design document
- [B] `P1.4.5.1` Complete City 5 design document
- [B] `P1.4.6.1` Complete City 6 design document
- [B] `P1.4.7.1` Complete City 7 design document
- [B] `P1.4.8.1` Complete City 8 design document
- [B] `P1.4.9.1` Complete City 9 design document
- [B] `P1.4.10.1` Complete City 10 design document

### Towns (10 total)
- [B] `P1.4.11.1` Complete Town 1 design document
- [B] `P1.4.12.1` Complete Town 2 design document
- [B] `P1.4.13.1` Complete Town 3 design document
- [B] `P1.4.14.1` Complete Town 4 design document
- [B] `P1.4.15.1` Complete Town 5 design document
- [B] `P1.4.16.1` Complete Town 6 design document
- [B] `P1.4.17.1` Complete Town 7 design document
- [B] `P1.4.18.1` Complete Town 8 design document
- [B] `P1.4.19.1` Complete Town 9 design document
- [B] `P1.4.20.1` Complete Town 10 design document

---

## 1.5 Dungeons 🔀 PARALLEL (after region docs)

Each dungeon document goes in `docs/phase1/dungeons/[dungeon-name].md`

### Dungeons 1-10 (Starter/Low Level)
- [B] `P1.5.1.1` Complete Tutorial Dungeon design document
  - Blocked by: P1.3.1.1
  - Scope: Create using DUNGEON_TEMPLATE
- [B] `P1.5.2.1` Complete Dungeon 2 design document
- [B] `P1.5.3.1` Complete Dungeon 3 design document
- [B] `P1.5.4.1` Complete Dungeon 4 design document
- [B] `P1.5.5.1` Complete Dungeon 5 design document
- [B] `P1.5.6.1` Complete Dungeon 6 design document
- [B] `P1.5.7.1` Complete Dungeon 7 design document
- [B] `P1.5.8.1` Complete Dungeon 8 design document
- [B] `P1.5.9.1` Complete Dungeon 9 design document
- [B] `P1.5.10.1` Complete Dungeon 10 design document

### Dungeons 11-20 (Mid Level)
- [B] `P1.5.11.1` Complete Dungeon 11 design document
- [B] `P1.5.12.1` Complete Dungeon 12 design document
- [B] `P1.5.13.1` Complete Dungeon 13 design document
- [B] `P1.5.14.1` Complete Dungeon 14 design document
- [B] `P1.5.15.1` Complete Dungeon 15 design document
- [B] `P1.5.16.1` Complete Dungeon 16 design document
- [B] `P1.5.17.1` Complete Dungeon 17 design document
- [B] `P1.5.18.1` Complete Dungeon 18 design document
- [B] `P1.5.19.1` Complete Dungeon 19 design document
- [B] `P1.5.20.1` Complete Dungeon 20 design document

### Dungeons 21-30 (End Game)
- [B] `P1.5.21.1` Complete Dungeon 21 design document
- [B] `P1.5.22.1` Complete Dungeon 22 design document
- [B] `P1.5.23.1` Complete Dungeon 23 design document
- [B] `P1.5.24.1` Complete Dungeon 24 design document
- [B] `P1.5.25.1` Complete Dungeon 25 design document
- [B] `P1.5.26.1` Complete Dungeon 26 design document
- [B] `P1.5.27.1` Complete Dungeon 27 design document
- [B] `P1.5.28.1` Complete Dungeon 28 design document
- [B] `P1.5.29.1` Complete Dungeon 29 design document
- [B] `P1.5.30.1` Complete Dungeon 30 design document

---

# PHASE 2: CHARACTER DESIGN

## 2.1 Player Character

### 2.1.1 Race & Body
- [B] `P2.1.1.1` Decide single vs multiple races
  - Blocked by: P0.4.2.5
  - Scope: Update DESIGN_DECISIONS.md
- [B] `P2.1.1.2` Define Human race (lore, appearance, starting location)
  - Blocked by: P2.1.1.1
  - Scope: Create docs/phase2/player/races.md
- [B] `P2.1.1.3` Define additional races (if applicable)
  - Blocked by: P2.1.1.1
- [B] `P2.1.1.4` Define body type options
  - Blocked by: P2.1.1.1
- [B] `P2.1.1.5` Define height options
  - Blocked by: P2.1.1.1

### 2.1.2 Appearance Options 🔀 PARALLEL
- [B] `P2.1.2.1` Define skin tone palette
  - Blocked by: P2.1.1.2
  - Scope: Create docs/phase2/player/customization.md
- [B] `P2.1.2.2` Define face options
  - Blocked by: P2.1.1.2
- [B] `P2.1.2.3` Define hair styles and colors
  - Blocked by: P2.1.1.2
- [B] `P2.1.2.4` Define facial hair options
  - Blocked by: P2.1.1.2

### 2.1.3 Starting Equipment
- [B] `P2.1.3.1` Define starting outfit options
  - Blocked by: P2.1.1.2
  - Scope: Create docs/phase2/player/starting-gear.md
- [B] `P2.1.3.2` Define starting equipment stats
  - Blocked by: P2.1.3.1
- [B] `P2.1.3.3` Define starting inventory
  - Blocked by: P2.1.3.1

### 2.1.4 Character Creation UI
- [B] `P2.1.4.1` Design character creation flow
  - Blocked by: P2.1.2.1-4, P2.1.3.1
  - Scope: Create docs/phase2/player/character-creation-ui.md

### 2.1.5 Player Animations
- [B] `P2.1.5.1` Define required player animations list
  - Blocked by: P2.1.1.2
  - Scope: Create docs/phase2/player/animations.md

---

## 2.2 NPCs

### 2.2.1 NPC System Design
- [B] `P2.2.1.1` Define NPC archetype categories
  - Blocked by: P0.4.3.5
  - Scope: Create docs/phase2/npcs/npc-system.md
- [B] `P2.2.1.2` Create NPC naming conventions
  - Blocked by: P1.1.3.1-6
- [B] `P2.2.1.3` Define NPC dialogue style guide
  - Blocked by: P0.4.2.4
- [B] `P2.2.1.4` Create NPC visual design guidelines
  - Blocked by: P0.4.5.1
- [B] `P2.2.1.5` Define NPC behavior patterns
  - Blocked by: P0.3.6.2

### 2.2.2 NPC Rosters 🔀 PARALLEL
- [B] `P2.2.2.1` Create Starting Region NPC roster
  - Blocked by: P1.3.1.1, P2.2.1.1
  - Scope: Create docs/phase2/npcs/rosters/starting-region.md
- [B] `P2.2.2.2` Create Region 2 NPC roster
  - Blocked by: P1.3.2.1, P2.2.1.1
- [B] `P2.2.2.3` Create Region 3 NPC roster
- [B] `P2.2.2.4` Create Region 4 NPC roster
- [B] `P2.2.2.5` Create Region 5 NPC roster
- [B] `P2.2.2.6` Create Region 6 NPC roster
- [B] `P2.2.2.7` Create Region 7 NPC roster
- [B] `P2.2.2.8` Create Region 8 NPC roster
- [B] `P2.2.2.9` Create Region 9 NPC roster
- [B] `P2.2.2.10` Create Region 10 NPC roster
- [B] `P2.2.2.11` Create Region 11 NPC roster
- [B] `P2.2.2.12` Create Region 12 NPC roster
- [B] `P2.2.2.13` Create Region 13 NPC roster

### 2.2.3 Major NPCs 🔀 PARALLEL
Each major NPC: docs/phase2/npcs/major/[npc-name].md using NPC_TEMPLATE
- [B] `P2.2.3.1` - `P2.2.3.50` Complete 50 major NPC profiles
  - Blocked by: P2.2.2.X (respective region roster)

### 2.2.4 Generic NPCs
- [B] `P2.2.4.1` Design generic guard types (per faction)
  - Blocked by: P2.2.1.4
  - Scope: Create docs/phase2/npcs/generic/guards.md
- [B] `P2.2.4.2` Design generic merchant types
  - Blocked by: P2.2.1.4
- [B] `P2.2.4.3` Design generic villager types
  - Blocked by: P2.2.1.4
- [B] `P2.2.4.4` Write generic NPC dialogue
  - Blocked by: P2.2.1.3

---

## 2.3 Monsters

### 2.3.1 Monster System Design
- [B] `P2.3.1.1` Define monster type categories
  - Blocked by: P0.4.2.1
  - Scope: Create docs/phase2/monsters/monster-system.md
- [B] `P2.3.1.2` Define monster tier system
  - Blocked by: P2.3.1.1
- [B] `P2.3.1.3` Create monster naming conventions
  - Blocked by: P2.3.1.1
- [B] `P2.3.1.4` Define monster stat scaling
  - Blocked by: P0.3.6.3
- [B] `P2.3.1.5` Define monster drop table structure
  - Blocked by: P2.3.1.2

### 2.3.2 Monster Rosters 🔀 PARALLEL
- [B] `P2.3.2.1` Create Starting Region monster roster
  - Blocked by: P1.3.1.1, P2.3.1.1
  - Scope: Create docs/phase2/monsters/rosters/starting-region.md
- [B] `P2.3.2.2` - `P2.3.2.13` Create Region 2-13 monster rosters
  - Blocked by: P1.3.X.1, P2.3.1.1

### 2.3.3 Monster Types 🔀 PARALLEL
Each monster: docs/phase2/monsters/types/[monster-name].md using MONSTER_TEMPLATE
- [B] `P2.3.3.1` - `P2.3.3.50` Complete 50 monster type profiles
  - Blocked by: P2.3.2.X (respective region roster)

---

## 2.4 Bosses

### 2.4.1 Boss System Design
- [B] `P2.4.1.1` Define boss categories
  - Blocked by: P2.3.1.1
  - Scope: Create docs/phase2/bosses/boss-system.md
- [B] `P2.4.1.2` Define boss difficulty tiers
  - Blocked by: P2.4.1.1
- [B] `P2.4.1.3` Define boss reward structure
  - Blocked by: P2.4.1.1, P2.3.1.5
- [B] `P2.4.1.4` Define boss respawn mechanics
  - Blocked by: P2.4.1.1

### 2.4.2 Boss Profiles 🔀 PARALLEL
Each boss: docs/phase2/bosses/[boss-name].md using BOSS_TEMPLATE
- [B] `P2.4.2.1` Complete Tutorial Boss profile
  - Blocked by: P1.5.1.1, P2.4.1.1-4
- [B] `P2.4.2.2` - `P2.4.2.20` Complete Bosses 2-20 profiles
  - Blocked by: P1.5.X.1, P2.4.1.1-4

---

# TASK STATISTICS

| Phase | Available | Blocked | In Progress | Complete | Total |
|-------|-----------|---------|-------------|----------|-------|
| Phase 0 | ~45 | ~70 | 0 | 0 | ~115 |
| Phase 1 | 0 | ~100 | 0 | 0 | ~100 |
| Phase 2 | 0 | ~85 | 0 | 0 | ~85 |
| **Total** | **~45** | **~255** | **0** | **0** | **~300** |

Note: This is a condensed task list. Full expansion (with all 50 NPCs, 50 monsters, etc. broken out) yields ~1,950 tasks.
