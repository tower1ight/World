```ds-statblock
"name": "Ankheg"
"ancestry":
- "Monster"
"roles":
- "SOLO"
"level": !!int "1"
"ev": !!int "60"
"stamina": !!int "120"
"immunities": []
"weaknesses": []
"speed": "5 ([[Burrow|burrow]])"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "3"
"intuition": !!int "1"
"agility": !!int "1"
"reason": !!int "-3"
"presence": !!int "-4"
"traits":
- "name": "Solo Monster"
  "effect": "- **Solo Turns**: The ankheg takes two turns each round. They can use\
    \ two actions on each of their turns, and can take each turn after any enemy's\
    \ turn. While [[Dazed|dazed]], the ankheg can take one action and one maneuver per turn.\
    \ - **End Effect**: At the end of their turn, the ankheg can take 5 damage to\
    \ end one save ends effect affecting them. This damage can't be reduced in any\
    \ way."
- "name": "Soft Underbelly"
  "effect": "A [[Prone|prone]] creature gains an edge on melee attacks against the ankheg instead\
    \ of taking a bane."
- "name": "Earthwalk"
  "effect": "[[Difficult Terrain|Difficult terrain]] composed of earth or loose rock doesn't cost the ankheg\
    \ extra movement."
- "name": "Tunneler"
  "effect": "When the ankheg [[Burrow|burrows]], they create a size 2 tunnel. The tunnel remains\
    \ stable for one day, then collapses."
"abilities":
- "name": "Bite"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage"
    "t2": "8 damage; [[Grabbed|grabbed]]"
    "t3": "11 damage; [[Grabbed|grabbed]]"
  - "name": "Effect"
    "effect": "A size 1 target [[Grabbed|grabbed]] this way takes 8 acid damage at the start of\
      \ each of their turns. "
- "name": "Claws"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; A2 [[Grabbed|grabbed]]"
    "t2": "4 damage; A3 [[Grabbed|grabbed]]"
    "t3": "5 damage; A4 [[Grabbed|grabbed]]"
  - "name": "2 Malice"
    "effect": "The ankheg can vertical slide one or both targets up to 5 squares. "
- "name": "Earth Eruption"
  "type": "Action"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  "distance": "4 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 damage"
    "t2": "6 damage"
    "t3": "7 damage; push 2 "
  - "name": "Effect"
    "effect": "The ankheg [[Burrow|burrows]] up to their speed, then creates the burst when they\
      \ breach the surface."
- "name": "Dust Cloud"
  "type": "Maneuver"
  "keywords":
  - "Area"
  "distance": "1 burst"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "The ground around the ankheg becomes [[Difficult Terrain|difficult terrain]]. While the ankheg\
      \ remains in their current space, they have concealment until the start of their\
      \ next turn. "
- "name": "Skitter"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "trigger": "A creature damages the ankheg"
  "effects":
  - "name": "Effect"
    "effect": "The ankheg shifts up to 3 squares. "
- "name": "Acid Breath"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "10 x 1 line within 1"
  "target": "Each creature in the line"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "4 acid damage"
    "t2": "6 acid damage"
    "t3": "7 acid damage"
  - "name": "Effect"
    "effect": "The ground within the area is covered in a puddle of acid that lasts\
      \ until the end of the encounter. A creature who enters the area for the first\
      \ time in a round or starts their turn there takes 2 acid damage. "
- "name": "Sinkhole"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The ankheg shifts up to their speed by burrowing. If the ankheg ends\
      \ this move underground and within 2 squares of a creature on the surface, the\
      \ ankheg makes a Bite attack against the creature. "
- "name": "Acid and Claws"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "2 burst"
  "target": "Each creature in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 acid damage; M2 [[Bleeding|bleeding]] (save ends)"
    "t2": "7 acid damage; M3 [[Bleeding|bleeding]] (save ends)"
    "t3": "10 acid damage; M4 [[Bleeding|bleeding]] (save ends)"

```
