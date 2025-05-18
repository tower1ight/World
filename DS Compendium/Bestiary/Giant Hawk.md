```ds-statblock
"name": "Giant Hawk"
"ancestry":
- "Animal"
"roles":
- "Mount"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "7 (flying)"
"size": "2"
"stability": !!int "0"
"free_strike": !!int "3"
"might": !!int "2"
"intuition": !!int "1"
"agility": !!int "2"
"reason": !!int "-3"
"presence": !!int "-2"
"traits":
- "name": "Mounted Platform"
  "effect": "Any creature riding the hawk can make a [[Free Strike|free strike]] during or after the\
    \ hawk's movement."
"abilities":
- "name": "Talons"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; M2 [[Grabbed|grabbed]]"
    "t2": "5 damage; M3 [[Grabbed|grabbed]]"
    "t3": "7 damage; [[Grabbed|grabbed]] "
- "name": "Dive"
  "type": "Maneuver"
  "effects":
  - "name": "Effect"
    "effect": "The hawk moves up to their speed. "

```
