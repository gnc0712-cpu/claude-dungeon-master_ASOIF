# Houses, Honor & Intrigue

Lightweight tracked mechanics for the political side of the game. These layer on top of standard D&D 5e checks — they don't replace ability checks, they give the *results* of social/political play somewhere to accumulate and matter.

Track these three numbers per character (and optionally per House) in `characters/[name].md` and `state.md`.

## The Three Tracks

### Honor (-3 to +3)

How much a character keeps their word, respects guest right, and abides by the codes of chivalry/oath-keeping — as *perceived*, not necessarily as *practiced in secret*.

| Honor | Meaning | Effect |
|---|---|---|
| +3 | A byword for honesty ("as honorable as a Stark," or your own local standard) | Advantage on Persuasion when invoking your word; NPCs who value honor seek you out |
| +1 to +2 | Known as trustworthy | +1 to +2 circumstance bonus on relevant social checks with honor-valuing NPCs |
| 0 | Unknown/neutral quantity | No modifier |
| -1 to -2 | Reputation for broken oaths or dishonorable acts | Disadvantage on Persuasion with honor-valuing NPCs; some refuse to deal with you at all |
| -3 | Infamous oathbreaker | Actively hunted or shunned by honor-bound factions (knights, the Watch, godswood-oath cultures) |

**Shift Honor** when a character publicly keeps or breaks a significant oath, violates or upholds guest right, wins or loses a trial by combat under suspicious circumstances, or otherwise makes a defining public choice. Shift by 1, rarely more, and only for choices witnessed or later discovered — secret sins don't move the track until exposed.

### Renown (0-5) and Infamy (0-5)

Two separate tracks — a character can have both. Renown is "known for something admirable or impressive"; Infamy is "known for something feared or reviled." They don't cancel out — a character can be both renowned as a duelist and infamous as a raider.

| Tier | Renown means | Infamy means |
|---|---|---|
| 0 | Nobody outside your own household knows your name | — |
| 1 | Known locally (a town, a Watch castle, a warband) | Locally feared/disliked |
| 2 | Known across a region | Regionally feared |
| 3 | Known across a kingdom/large area | Kingdom-wide dread or hatred |
| 4 | Known across Westeros or a comparable span of Essos | Continent-wide infamy |
| 5 | A name every smallfolk and lord alike has heard | Legendary villain — sung about, warned about, hunted |

**Gain tiers** through in-fiction accomplishment: winning a notable duel or tourney event, surviving something that should have killed you (and word getting out), a decisive battlefield feat, uncovering or foiling a major plot, a marriage alliance, a kinslaying, a massacre, breaking guest right, or any act dramatic enough that singers or gossips would carry it. Renown/Infamy should move slowly — reserve tier gains for session-defining moments, not routine wins.

**Use it**: Higher Renown means NPCs recognize the character on sight (roleplay this — no mechanical bonus by default), unlocks audiences with higher-status NPCs who'd otherwise ignore a nobody, and can grant advantage on Persuasion/Intimidation checks where the reputation is directly relevant. Higher Infamy does the same in reverse, plus makes the character a target — bounty hunters, honor-bound enemies, or opportunists looking to make their own name.

## House Standing

For campaigns where the party represents or serves a House (their own, or one they're sworn to), track a simple **House Standing** score (0-5, same tier meanings as Renown) representing the House's overall power/prestige, and note its major relationships:

```markdown
## House [Name]
- **Seat**: [Castle/holdfast]
- **Region**: [Where]
- **Words**: [House motto, if any]
- **Sigil**: [Heraldry]
- **Standing**: [0-5]
- **Liege**: [Who they answer to, if anyone]
- **Bannermen/Vassals**: [Who answers to them, if anyone]
- **Allies**: [Houses/factions, and why]
- **Rivals/Enemies**: [Houses/factions, and why]
- **Resources**: [Levies, wealth, notable assets]
- **Succession**: [Who's next in line, any disputes]
```

House Standing shifts with the fortunes of the party's political play: winning or losing a marriage alliance, a battle, a court case, a harvest, or a scandal. Move it rarely and deliberately — it's the campaign's political scoreboard.

## Resolving Intrigue

Most political maneuvering is still just ability checks (Persuasion, Deception, Insight, Intimidation, Investigation, sometimes History or Religion) with the stakes and DC set by context, same as any other challenge. Layer in:

- **Advantage/disadvantage from the tracks above** where reputation is directly relevant to the specific ask.
- **Guest Right**: Once food and drink are shared under a host's roof, both host and guest are bound by an old and sacred taboo against violence toward one another for the duration of the stay. Breaking it is one of the few acts serious enough to justify an immediate, large Honor/Infamy shift and can turn entire Houses into blood enemies. Foreshadow it as a real weight in the fiction before anyone breaks it.
- **Trial by Combat**: A character accused of a crime (or a lord settling a dispute) may demand trial by combat — a duel (or a champion fighting in their place) whose outcome is treated in-world as divine judgment, regardless of what actually happened. Resolve as a standard combat encounter; the social/legal consequences follow the fictional outcome, not the "truth."
- **Wardship & Fostering**: Highborn children are commonly sent to be raised in another House's household — a useful backstory hook, hostage-adjacent leverage, or source of unlikely friendships/rivalries between PCs and NPCs.
- **Information as currency**: Secrets, marriage prospects, and old grudges are the real treasure of the political game. Let players spend a session's worth of successful intrigue checks accumulating leverage rather than resolving everything in one roll.

Keep the numbers light-touch — they exist to give consequences memory, not to become a second combat system. When in doubt, resolve with a standard ability check and let the track shift only for the moments that would actually get talked about at a feast.
