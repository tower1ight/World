```ds-statblock
"name": "Wodenelg"
"ancestry":
- "Plant"
- "Wode Elf"
"roles":
- "Mount"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "30"
"immunities": []
"weaknesses": []
"speed": "10"
"size": "2"
"stability": !!int "1"
"free_strike": !!int "2"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "-1"
"presence": !!int "-1"
"traits":
- "name": "Sure Footed"
  "effect": "The wodenelg ignores all [[Difficult Terrain|difficult terrain]], including enemy squares,\
    \ and doesn't provoke opportunity attacks by moving."
- "name": "Mounted Stability"
  "effect": "The wodenelg's rider has **+3** to Stability."
- "name": "Shared Glamor"
  "effect": "If the wodenelg's rider has the Masking Glamor or [[Hunter]]'s Glamor trait,\
    \ they also gain the trait's benefits."
"abilities":
- "name": "Gore"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage"
  - "name": "Effect"
    "effect": "The wodenelg's rider can make a [[Free Strike|free strike]] at any point during the\
      \ [[Charge|charge]]. "
- "name": "Where I End the Woods Begin"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The wodenelg and their rider become invisible until the start of their\
      \ next turn. "

```
