# NPC Generation & Roleplay

Reference: `dnd-5e-srd/markdown/16 npcs.md`, `dnd-5e-srd/markdown/11 monsters.md`, `dm-instructions/setting-westeros.md`, `dm-instructions/houses-and-honor.md`

## Quick NPC Creation

For NPCs that need stats, use this quick framework (mechanically unchanged from core 5e — only the fictional label changes):

### By Role/CR

| Role | HP | AC | Attack | Damage | Save DC |
|------|----|----|--------|--------|---------|
| Smallfolk (CR 0) | 4 | 10 | +2 | 1d4 | 10 |
| Household Guard (CR 1/8) | 11 | 16 | +3 | 1d6+1 | 11 |
| Sellsword (CR 1/2) | 32 | 11 | +4 | 1d6+2 | 12 |
| Household Knight (CR 3) | 52 | 18 | +5 | 2d6+3 | 13 |
| Blooded War Veteran (CR 3) | 58 | 17 | +5 | 2d8+3 | 13 |
| Faceless Man / Master Assassin (CR 8) | 78 | 15 | +6 | 1d8+3 + 7d6 | 15 |
| Red Priest / Maester of forbidden lore (CR 6) | 40 | 12 | +6 | varies | 15 |

For other CRs, reference the SRD monsters file. Wildlife and monsters beyond the Wall (wights, cave bears, and the like) can be reskinned from the SRD's beast/undead stat blocks — see `dm-instructions/setting-westeros.md` for regional flavor to apply.

### Ability Scores Quick Reference

| Archetype | High | Medium | Low |
|-----------|------|--------|-----|
| Brute (raider, reaver) | Str, Con | Dex | Int, Wis, Cha |
| Schemer (spy, courtier) | Dex | Int, Cha | Str, Wis, Con |
| Maester/Scholar | Int, Wis | Cha | Str, Dex, Con |
| Lord/Lady, Leader | Cha | Wis, Int | Str, Dex, Con |
| Knight, Warrior | Str, Dex | Con | Int, Wis, Cha |

## Personality Generation

### Quick Traits (d6 each)

**Demeanor**:
1. Nervous, fidgety
2. Gruff, curt
3. Warm, welcoming
4. Suspicious, guarded
5. Arrogant, dismissive
6. Weary, resigned

**Motivation**:
1. Survival — just getting by
2. Ambition — climbing higher, a better marriage, a better seat
3. Loyalty — sworn to a House or oath
4. Vengeance — settling an old score
5. Duty — obligation over desire
6. Protection — keeping kin or House safe

**Secret**:
1. A bastard child, hidden or acknowledged
2. In debt to a dangerous lender (the Iron Bank, a crime lord)
3. Knows something about the succession they shouldn't
4. Not who they claim to be — false name, false House
5. Broke guest right once, and it's never spoken of
6. Secretly practices a faith their House would punish

### Physical Quirks (d8)
1. Missing fingers/ear (old war or punishment)
2. Distinctive scar
3. Nervous tic
4. Unusual eye color
5. Walks with a limp (old wound)
6. Constantly fidgeting with a House token/sigil
7. Speaks with hands
8. Never makes eye contact with highborns

### Voice/Speech Patterns
- Speaks slowly, choosing words carefully (a courtier's habit)
- Fast talker, hard to interrupt
- Whispers everything
- Laughs at inappropriate times
- Uses elaborate, archaic vocabulary
- Heavy regional accent (Dornish lilt, Ironborn bluntness, Free Folk plainness)
- Stutters when nervous
- Quotes the Seven, the Old Gods, or a proverb constantly

## Roleplay Guidelines

### Making NPCs Memorable

1. **Immediate Hook**: Something visible or audible that distinguishes them instantly
2. **Clear Want**: What do they want from this conversation/scene — often tied to House interest, survival, or ambition
3. **Obstacle**: What's stopping them from getting it?
4. **Humanity**: One sympathetic or relatable detail, even in a villain

### Dialogue Principles

- **Don't monologue**: NPCs should respond, not lecture
- **React to players**: Adjust tone based on how PCs treat them, and on the party's Honor/Renown/Infamy (see `houses-and-honor.md`)
- **Information costs**: Important info requires persuasion, payment, marriage prospects, or favors — the political economy of Westeros runs on debts owed
- **Imperfect knowledge**: NPCs don't know everything; rumors travel by raven, ship, and gossip, and can be wrong or planted

### NPC Relationships

Track how NPCs and Houses feel about the party:
- **Hostile**: Will work against them, may attack, may call banners
- **Unfriendly**: Won't help, might hinder or gossip against them
- **Indifferent**: No investment either way
- **Friendly**: Willing to help within reason
- **Allied**: Actively supports, takes political or martial risks for them

Actions shift relationships. Oaths and promises made should be tracked and remembered — broken vows are remembered longest.

## Named NPC Template

For important recurring NPCs:

```markdown
## [Name]

**Role**: [Occupation/Position]
**House/Allegiance**: [If any]
**Location**: [Where typically found]
**Appearance**: [Brief physical description]

**Personality**: [2-3 key traits]
**Motivation**: [What drives them]
**Secret**: [Hidden truth]
**Voice**: [How they speak]

**Relationship to Party**: [Current standing]
**Useful For**: [What they can offer PCs]

**Stats** (if needed):
- Use [X] stat block from SRD
- Or: AC [X], HP [X], Attack +[X] for [damage]
```

## Improvised NPCs

When players interact with an unexpected NPC:

1. **Assign immediate traits**: Pick one demeanor, one physical quirk
2. **Determine knowledge level**: What would they realistically know?
3. **Note them down**: If interaction is significant, record for consistency
4. **Give them a name**: Even minor NPCs become memorable with names

### Name Banks

Keep ready, organized by culture (see `dm-instructions/setting-westeros.md` for the cultures themselves):

**First Men (North, Riverlands old stock)**:
- Male: Brandon, Cregan, Domeric, Eddard, Jorah, Rickard, Torrhen, Willam
- Female: Alysanne, Berena, Cerelle, Jonelle, Lyanna, Sarra, Wynafryd

**Andal (most of the southern Seven Kingdoms)**:
- Male: Aldric, Bram, Cedric, Dorian, Edmund, Gareth, Harys, Lucan
- Female: Alena, Cordelia, Delia, Elena, Falyse, Genna, Marya

**Ironborn**:
- Male: Balon, Dagon, Euron, Harlon, Rodrik, Torgon, Urragon
- Female: Alannys, Asha, Gwynesse, Nolla, Wynafrei

**Dornish/Rhoynar**:
- Male: Anders, Daemon, Deziel, Manfrey, Qorgyle, Ryon
- Female: Ariane, Delonne, Nymeria, Obara, Sarella, Tyene

**Free Folk**:
- Male: Craster, Halleck, Rattleshirt, Styr, Tormund, Varamyr
- Female: Gilly, Ivy, Osha, Rowan, Val, Ygritte-adjacent originals

**Braavosi/Essosi**:
- Male: Bravos, Jaqen, Merello, Rugello, Tycho, Vaes
- Female: Daenella, Meralyn, Quaithe-adjacent, Talisa-adjacent, Zalla

**Dothraki**:
- Male: Drogo-adjacent, Jhaqo, Khal, Moro, Qotho, Rakharo
- Female: Doreah-adjacent, Irri, Jhiqui, Malakho, Zhoe

Vary and invent freely — these are seeds, not an exhaustive list. Avoid reusing named canon protagonists as your NPCs; take the naming *conventions*, not the specific characters.

## Factions & Houses

When creating a House or organization, use the House template in `dm-instructions/houses-and-honor.md`. For non-House factions (Faceless Men, a mercenary company, a smuggling ring, a religious order):

1. **Goal**: What does the faction want?
2. **Methods**: How do they pursue it?
3. **Symbol**: Visual identifier
4. **Leader**: Named NPC at the top
5. **Agent types**: What members do PCs encounter?
6. **Resources**: What can they bring to bear?
7. **Enemies**: Who opposes them?
