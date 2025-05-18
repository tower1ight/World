```ds-statblock
"name": "Goblin Warrior"
"ancestry":
- "Goblin"
- "Humanoid"
"roles":
- "Harrier"
"level": !!int "1"
"ev": !!int "10"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "6 (climb)"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "-2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "-1"
"traits":
- "name": "Crafty"
  "effect": "The warrior doesn't provoke opportunity attacks by moving."
"abilities":
- "name": "Spear"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage "
- "name": "Bury the Point"
  "type": "Action"
  "cost": "2 Malice"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; M1 [[Bleeding|bleeding]] (save ends)"
    "t2": "7 damage; M2 [[Bleeding|bleeding]] (save ends)"
    "t3": "8 damage; M3 [[Bleeding|bleeding]] (save ends) "

```
