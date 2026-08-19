# Spellcasting

Reference: `dnd-5e-srd/markdown/08 spellcasting.md`, `dm-instructions/setting-westeros.md`, `dm-instructions/character-sheets.md`

## Magic in a Low-Magic World

True magic is rare and mostly disbelieved by ordinary people — septons preach against it, maesters study it skeptically, and most smallfolk have never witnessed it firsthand. **Player spellcasters are the deliberate exception**: they get full, unmodified standard 5e spellcasting exactly as written below — no reduced slots, no extra costs, no restricted spell lists. What changes is entirely narrative:

- **Reflavor the source and delivery** of every spell to match the class reflavoring in `dm-instructions/character-sheets.md` (a red priest's fire-scrying, a maester's forbidden higher mysteries, a warg's greenseeing, a Faceless Man's poisons-and-faces craft, etc.) rather than generic D&D spell names.
- **Play the world's reaction honestly.** A PC casting a visible spell in front of smallfolk, a septon, or a rival House should provoke fear, rumor, religious alarm, or opportunistic blackmail — not a shrug. This is a roleplay/consequence layer, not a mechanical nerf.
- **Rare doesn't mean secret by default** — a party can absolutely include an openly magical character (a known red priestess, a maester who's shed pretense) — just make sure the *social* cost of that visibility is real and tracked (see Honor/Renown/Infamy in `dm-instructions/houses-and-honor.md`).
- **NPC spellcasters should stay rare** by contrast — most NPC "magic" the party encounters should be legend, fraud, ambiguous omens, or genuinely dangerous when it's real, reinforcing why the PC's own power feels exceptional.

## Spell Slot Tracking

### Slots by Class Level

**Full Casters** (Bard, Cleric, Druid, Sorcerer, Wizard):

| Level | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
|-------|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| 1 | 2 | - | - | - | - | - | - | - | - |
| 2 | 3 | - | - | - | - | - | - | - | - |
| 3 | 4 | 2 | - | - | - | - | - | - | - |
| 4 | 4 | 3 | - | - | - | - | - | - | - |
| 5 | 4 | 3 | 2 | - | - | - | - | - | - |
| 6 | 4 | 3 | 3 | - | - | - | - | - | - |
| 7 | 4 | 3 | 3 | 1 | - | - | - | - | - |
| 8 | 4 | 3 | 3 | 2 | - | - | - | - | - |
| 9 | 4 | 3 | 3 | 3 | 1 | - | - | - | - |
| 10 | 4 | 3 | 3 | 3 | 2 | - | - | - | - |

**Half Casters** (Paladin, Ranger): Use half level (rounded down) on the table above, starting at level 2.

**Third Casters** (Eldritch Knight, Arcane Trickster): Use third level (rounded down) on the table above, starting at level 3.

**Warlock Pact Magic**: Different system—slots recover on short rest:

| Level | Slots | Slot Level |
|-------|-------|------------|
| 1 | 1 | 1st |
| 2 | 2 | 1st |
| 3-4 | 2 | 2nd |
| 5-6 | 2 | 3rd |
| 7-8 | 2 | 4th |
| 9+ | 2 | 5th |

Plus Mystic Arcanum at higher levels (1/long rest each).

## Concentration

### Rules
- Only one concentration spell at a time
- Casting another concentration spell ends the first
- Taking damage: Constitution save (DC = 10 or half damage, whichever higher)
- Being incapacitated or killed ends concentration
- Environmental interference (DM discretion)

### Tracking
Mark concentration spells clearly when cast:
```
[CONCENTRATING: Bless, 8 rounds remaining]
```

Prompt for concentration saves when the caster takes damage.

## Spell Components

| Component | Requirement |
|-----------|-------------|
| **V** (Verbal) | Must be able to speak; fails if silenced |
| **S** (Somatic) | At least one free hand; fails if restrained |
| **M** (Material) | Component pouch OR spellcasting focus OR specific item |

### Material Component Rules
- Components without gold cost: Replaced by focus or component pouch
- Components with gold cost: Must have the specific item
- Components consumed: Must be replaced after casting
- Components not consumed: Can be reused indefinitely

Example: *Revivify* requires diamonds worth 300 gp which ARE consumed.

## Ritual Casting

### Rules
- Spell must have ritual tag
- Takes 10 minutes longer than normal casting time
- Does not expend a spell slot
- Must have spell prepared (or in spellbook for Wizards)

### Classes with Ritual Casting
- **Bard**: Must know the spell
- **Cleric**: Must have prepared the spell
- **Druid**: Must have prepared the spell
- **Wizard**: Spell must be in spellbook (doesn't need to be prepared)

## Casting Time

| Time | Effect |
|------|--------|
| **1 action** | Standard combat casting |
| **1 bonus action** | Can also take action, but only for cantrips |
| **1 reaction** | Triggered by specific condition |
| **1 minute** | 10 rounds in combat, or narrative time |
| **10 minutes** | Ritual time or preparation |
| **1 hour+** | Extended casting, usually out of combat |

### Bonus Action Spell Rule
If you cast a spell as a bonus action, you can only cast a cantrip with your action that turn.

## Spell Attacks and Saves

### Attack Rolls
```
d20 + Spellcasting Ability Modifier + Proficiency Bonus
```

### Save DC
```
8 + Spellcasting Ability Modifier + Proficiency Bonus
```

### Spellcasting Ability by Class
| Class | Ability |
|-------|---------|
| Bard | Charisma |
| Cleric | Wisdom |
| Druid | Wisdom |
| Paladin | Charisma |
| Ranger | Wisdom |
| Sorcerer | Charisma |
| Warlock | Charisma |
| Wizard | Intelligence |

## Counterspell and Dispel Magic

### Counterspell
- Reaction when you see a creature within 60 ft casting
- 3rd level slot: Automatically counters spells of 3rd level or lower
- Higher level spell: Ability check DC 10 + spell level
- Can upcast Counterspell to automatically counter spells of that level or lower

### Dispel Magic
- Action to end spells on a target
- 3rd level slot: Ends spells of 3rd level or lower
- Higher level spells: Ability check DC 10 + spell level
- Can upcast to automatically end spells of that level or lower

## Describing Magic

Make spellcasting feel significant:

**Mechanical**: "I cast Fireball."

**Better**: "The red priestess spreads her arms and cries out to R'hllor in High Valyrian, and the brazier fire behind her leaps sideways through the air, a comet of flame streaking toward the raiders — the smallfolk nearby drop to their knees, crying out for the Lord of Light or crossing themselves against the Stranger..."

Consider:
- **Verbal**: What language? What tone? Ancient words, sung phrases, shouted commands?
- **Somatic**: Elegant gestures? Violent motions? Subtle finger movements?
- **Visual**: What does the magic look like? Color, texture, sound?
- **Feel**: Does it smell like ozone? Feel cold? Raise hair on arms?

## Spell Slot Recovery

| Method | Effect |
|--------|--------|
| **Long Rest** | All spell slots recovered |
| **Arcane Recovery** (Wizard) | Short rest, recover slots = half wizard level (rounded up), once per day |
| **Font of Magic** (Sorcerer) | Convert sorcery points to slots and vice versa |
| **Pact Magic** (Warlock) | All pact slots recover on short rest |

## Common Spell Rulings

### Line of Sight vs Line of Effect
- Most spells require clear path to target
- Glass blocks line of effect but not sight
- Total cover blocks both

### Areas of Effect
- **Cone**: Starts at origin point, widens
- **Cube**: Origin on one face
- **Cylinder**: Origin at center of circular base
- **Line**: Straight from origin in direction of choice
- **Sphere**: Origin at center

### Stacking
- Same spell from different sources doesn't stack (most potent applies)
- Different spells stack
- Same spell at different levels: use higher level effect
