# Combat Rules

Reference: `dnd-5e-srd/markdown/07 combat.md`, `dnd-5e-srd/markdown/12 conditions.md`, `dm-instructions/houses-and-honor.md`

Mechanics below are unchanged from core 5e. Weapons should be period-flavored: longswords, arming swords, war hammers, morningstars, lances, halberds, longbows, crossbows, and daggers — no firearms or exotic modern weapons. Dragonglass and Valyrian steel are covered in `dm-instructions/items-and-loot.md`.

## Trial by Combat & Formal Duels

A distinct kind of fight from a battlefield skirmish — the stakes are legal/political, not just survival:

- **Trial by Combat**: An accused party (or their champion) fights an accuser's champion; the outcome is treated in-world as the judgment of the gods, regardless of the literal facts of the case. Run it as a standard combat encounter — often 1v1, sometimes with seconds — but make sure both sides understand going in that losing means accepting the legal consequence (execution, forfeiture, exile), not just HP loss.
- **Formal Duels**: Tourney matches, trials of honor, or a duel to settle an insult. These can be run to the death, to first blood (first HP loss below a threshold, or first successful hit), or to yield (either combatant may call it — refusing a yield when clearly beaten is itself a notable act, worth an Honor/Infamy shift per `houses-and-honor.md`).
- Both types deserve narration weight beyond a normal fight — an audience, formality, and consequences that outlast the encounter.

## Initiative & Turn Order

When combat begins:

1. **Determine Surprise**: If one side is unaware, they are surprised (can't act on first turn, no reactions until turn ends)
2. **Roll Initiative**: Each combatant rolls d20 + Dexterity modifier
3. **Establish Order**: Highest to lowest. Ties: compare Dex modifiers, then player choice

Display initiative as a clear tracker:
```
INITIATIVE
----------
1. [17] Cregan (PC) - 45/45 HP
2. [15] Raider Chief - ??/?? HP
3. [12] Marya (PC) - 32/38 HP
4. [8]  Raiders x3 - ??/?? HP
```

Update HP and conditions as combat progresses.

## Action Economy

Each turn, a creature can take:

| Type | Examples |
|------|----------|
| **Movement** | Move up to speed (can split before/after action) |
| **Action** | Attack, Cast Spell, Dash, Disengage, Dodge, Help, Hide, Ready, Search, Use Object |
| **Bonus Action** | Class features, certain spells (only if something grants one) |
| **Reaction** | Opportunity attack, some spells (Shield, Counterspell), readied actions |
| **Free Interaction** | Draw/sheathe weapon, open door, speak briefly |

## Attack Resolution

### Melee/Ranged Attacks
1. Player declares target and attack
2. Roll d20 + attack modifier vs target AC
3. **Natural 20**: Critical hit (double damage dice)
4. **Natural 1**: Automatic miss
5. On hit: Roll damage dice + modifier

### Spell Attacks
- Attack roll spells: d20 + spellcasting modifier + proficiency
- Saving throw spells: DC = 8 + spellcasting modifier + proficiency

## Damage & Healing

- **Damage Types**: Bludgeoning, Piercing, Slashing, Fire, Cold, Lightning, Thunder, Poison, Acid, Necrotic, Radiant, Force, Psychic
- **Resistance**: Half damage
- **Vulnerability**: Double damage
- **Immunity**: No damage

### At 0 HP
1. Fall unconscious and prone
2. Begin making death saving throws on your turn
3. **Death Save**: d20, no modifiers
   - 10+: Success
   - 9 or below: Failure
   - Natural 20: Regain 1 HP, wake up
   - Natural 1: Two failures
4. **3 Successes**: Stabilized (unconscious but not dying)
5. **3 Failures**: Dead
6. Taking damage while at 0 HP = automatic failure (critical hit = 2 failures)

### Massive Damage
If remaining damage after hitting 0 HP equals or exceeds max HP: instant death.

## Common Conditions

| Condition | Effect |
|-----------|--------|
| **Blinded** | Auto-fail sight checks, attacks have disadvantage, attacks against have advantage |
| **Charmed** | Can't attack charmer, charmer has advantage on social checks |
| **Frightened** | Disadvantage while source visible, can't willingly move closer |
| **Grappled** | Speed 0, ends if grappler incapacitated or effect moves you out of reach |
| **Incapacitated** | No actions or reactions |
| **Invisible** | Heavily obscured, advantage on attacks, attacks against have disadvantage |
| **Paralyzed** | Incapacitated, auto-fail Str/Dex saves, attacks have advantage, hits within 5ft are crits |
| **Poisoned** | Disadvantage on attacks and ability checks |
| **Prone** | Disadvantage on attacks, melee attacks have advantage, ranged have disadvantage, stand costs half movement |
| **Restrained** | Speed 0, attacks have disadvantage, attacks against have advantage, Dex saves disadvantage |
| **Stunned** | Incapacitated, auto-fail Str/Dex saves, attacks have advantage |
| **Unconscious** | Incapacitated, drop items, fall prone, auto-fail Str/Dex saves, attacks have advantage, hits within 5ft are crits |

## Cover

- **Half Cover** (+2 AC, +2 Dex saves): Low wall, furniture, creatures
- **Three-Quarters Cover** (+5 AC, +5 Dex saves): Portcullis, arrow slit
- **Total Cover**: Can't be targeted directly

## Opportunity Attacks

Trigger: Enemy leaves your reach without Disengaging
- Uses reaction
- One melee attack

## Environmental Hazards

Describe dangers vividly and telegraph them fairly:
- **Difficult Terrain**: Half movement speed
- **Falling**: 1d6 bludgeoning per 10 feet (max 20d6)
- **Suffocation**: Minutes equal to 1 + Con modifier, then Con mod rounds before 0 HP
- **Fire**: Typically 1d10 fire damage, may ignite flammables

## Combat Narration

Don't just report numbers. Make combat visceral:

**Mechanical**: "You hit for 8 damage."

**Better**: "Your blade finds the gap between the raider's pauldron and breastplate. He staggers, snarling, dark blood welling from the wound. [8 damage]"

Describe:
- The physicality of attacks
- Enemy reactions (pain, fear, rage)
- Environmental consequences
- The tide of battle shifting
