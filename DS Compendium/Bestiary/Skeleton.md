```ds-statblock
"name": "Skeleton"
"ancestry":
- "Corporeal"
- "Undead"
"roles":
- "Artillery"
"level": !!int "1"
"ev": !!int "8"
"stamina": !!int "12"
"immunities":
- "Corruption 3"
- "Poison 3"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "-2"
"free_strike": !!int "4"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "1"
"presence": !!int "-1"
"traits":
- "name": "Arise"
  "effect": "The first time the skeleton is reduced to Stamina 0 by damage that isn't\
    \ fire damage or holy damage and their body isn't destroyed, they regain half\
    \ their Stamina and fall [[Prone|prone]]."
"abilities":
- "name": "Bone Shards"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 10"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage"
  - "name": "Effect"
    "effect": "Until the start of the skeleton's next turn, the target takes 2 damage\
      \ the first time they move on their turn. "
- "name": "Bone Spur"
  "type": "Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "1 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "1 damage; M1 [[Bleeding|bleeding]] (save ends)"
    "t2": "2 damage; M2 [[Bleeding|bleeding]] (save ends)"
    "t3": "3 damage; M3 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "Each target has a bane on their next attack until the start of the\
      \ skeleton's next turn. "

```
