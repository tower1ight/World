```ds-statblock
"name": "Ghost"
"ancestry":
- "Incorporeal"
- "Undead"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "20"
"stamina": !!int "40"
"immunities":
- "Corruption 5"
- "Poison 5"
"weaknesses": []
"speed": "6 ([[Fly|fly]])"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "2"
"might": !!int "-2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "3"
"traits":
- "name": "Phantom Flow"
  "effect": "Each incorporeal undead creature within 10 squares of the ghost ignores\
    \ [[Difficult Terrain|difficult terrain]]."
- "name": "Corruptive Phasing"
  "effect": "The ghost can move through other creatures and objects at normal speed.\
    \ The first time in a round that the ghost passes through a creature, that creature\
    \ takes 2 corruption damage."
"abilities":
- "name": "Heat Death"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 5"
  "target": "Two creatures"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 cold damage; P2 [[Slowed|slowed]] (save ends)"
    "t2": "5 cold damage; P3 [[Slowed|slowed]] (save ends)"
    "t3": "6 cold damage; P2 [[Slowed|slowed]] (save ends)"
  - "name": "Effect"
    "effect": "The next attack made against a target has edge. "
- "name": "Haunt"
  "type": "Maneuver"
  "keywords":
  - "Ranged"
  "distance": "Ranged 8"
  "target": "Self or one incorporeal ally"
  "effects":
  - "name": "Effect"
    "effect": "The target shifts up to their speed."
  - "name": "2 Malice"
    "effect": "The ghost chooses one additional target. "
- "name": "Shriek"
  "type": "Triggered Action"
  "cost": "1 Malice"
  "keywords":
  - "Magic"
  "distance": "Melee 1"
  "target": "The triggering creature"
  "trigger": "A creature within distance targets the ghost with an attack."
  "effects":
  - "name": "Effect"
    "effect": "The ghost has resistance against the attack, and the target takes 2\
      \ sonic damage. "
- "name": "Paranormal Activity"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "5 burst"
  "target": "Each size 1S or larger object in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target floats 1 square into the air and is pulled 5 squares toward\
      \ the nearest enemy within 3 squares of the target. "
- "name": "Spirited Away"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "5 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "PRS RR"
    "t1": "Levitated (EoE) (see effect)"
    "t2": "Levitated (EoT)"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "A levitated target floats 1 square off the ground when they are first\
      \ affected, then rises 1 square at the end of each of their turns. If a levitated\
      \ target can't already [[Fly|fly]], they can [[Fly|fly]] but are [[Slowed|slowed]] and [[Weakened|weakened]] while flying\
      \ in this way. "
- "name": "Awful Wail"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "5 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 sonic damage"
    "t2": "5 sonic damage"
    "t3": "5 sonic damage"
  - "name": "Effect"
    "effect": "P3: The target is reduced to 1 Stamina if they have 2 or more Stamina\
      \ after taking damage. "

```
