# Claude Dungeon Master: A Song of Ice and Fire

A D&D 5th Edition Dungeon Master system powered by Claude, reskinned for solo campaigns set in the world of **A Song of Ice and Fire** (Westeros, Essos, and the wider world of Planetos). Run dark, political, low-fantasy campaigns in your own original era and region — not a retelling of the books or show — where Houses, oaths, and steel matter more than spellbooks, and death is real.

## What This Is

This repository contains instructions and reference materials that turn Claude into a capable Dungeon Master for an ASOIAF-flavored D&D 5e game. It includes:

- **CLAUDE.md** - Core DM persona, tone guidelines, and session commands
- **dm-instructions/** - Detailed guidance for the setting, character creation, combat, NPCs/Houses, items, campaigns, and magic in a low-magic world:
  - `setting-westeros.md` - The world: geography, cultures, faiths, and how to place an original campaign in the timeline
  - `houses-and-honor.md` - Lightweight Honor / Renown / Infamy / House Standing mechanics for political play
  - `character-sheets.md` - Culture-of-origin (replaces D&D race) and class reflavoring (knights, red priests, Faceless Men, etc.)
  - `combat-rules.md` - Core 5e combat plus trial by combat and formal duels
  - `npc-generation.md` - Westerosi/Essosi name banks and NPC/House creation
  - `items-and-loot.md` - Westerosi coinage, Valyrian steel, dragonglass, poisons
  - `campaign-generation.md` - Campaign frames (Sworn House, Sellsword Company, Night's Watch, etc.), era templates, and adventure hooks
  - `spellcasting.md` - Full standard 5e spellcasting for PCs in a world where magic is otherwise rare and feared
- **dnd-5e-srd/** - Complete D&D 5e System Reference Document for rules lookup (the mechanical backbone; the `dm-instructions/` files layer the setting on top)

## Usage

1. Clone this repository
2. Open it with [Claude Code](https://claude.ai/claude-code) or add it as context in your Claude conversation
3. Start a new campaign or load an existing one — the DM will walk you through placing it in an era, region, and campaign frame (see `dm-instructions/setting-westeros.md`)

### Basic Commands

- `Start new campaign [name]` - Begin a new adventure
- `Load campaign [name]` - Resume an existing campaign
- `Create character` - Walk through character creation (culture of origin, House, class)
- `Show House [name]` - Display a House sheet
- `Save campaign` / `End session` - Save progress

Your campaign data will be stored in a local `campaigns/` folder (excluded from git).

## Credits

### D&D 5e SRD

The System Reference Document is provided under the Open Gaming License v1.0a.

- **Original Content**: Wizards of the Coast, Inc.
- **SRD 5.0 Authors**: Mike Mearls, Jeremy Crawford, Chris Perkins, Rodney Thompson, Peter Lee, James Wyatt, Robert J. Schwalb, Bruce R. Cordell, Chris Sims, and Steve Townshend
- **Based on original material by**: E. Gary Gygax and Dave Arneson
- **Markdown/JSON Conversion**: [Ben Morton](https://github.com/BTMorton/dnd-5e-srd) (MIT License, 2017)

### A Song of Ice and Fire

The Westeros/Essos setting concepts, cultures, faiths, and terminology referenced here draw on George R. R. Martin's *A Song of Ice and Fire* setting for fan, non-commercial creative use. This repository does not reproduce book/show text and is not affiliated with or endorsed by George R. R. Martin, HBO, or their publishers. All original campaign content generated with this system (Houses, characters, plots) is your own creation.

## License

- DM instructions and CLAUDE.md: MIT License
- D&D 5e SRD content: Open Gaming License v1.0a (see `dnd-5e-srd/LICENSE`)
