```ds-statblock
"name": "Radenwight Ratcrobat"
"ancestry":
- "Humanoid"
- "Radenwight"
"roles":
- "Harrier"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "30"
"immunities": []
"weaknesses": []
"speed": "7 (climb)"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "-1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Gymratstics"
  "effect": "The ratcrobat has an edge on attacks against larger creatures."
"abilities":
- "name": "En Garde!"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage"
  - "name": "Effect"
    "effect": "The ratcrobat can shift up to 2 squares after attacking the first target,\
      \ then can shift 1 square after attacking the second target. "
- "name": "Over Here, Thanks"
  "type": "Maneuver"
  "keywords":
  - "Melee"
  "distance": "Melee 1"
  "target": "One enemy"
  "effects":
  - "name": "Effect"
    "effect": "Slide 3; the ratcrobat can then shift into any of the squares the target\
      \ left. "
- "name": "Ready Rodent"
  "type": "Triggered Action"
  "keywords":
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature"
  "trigger": "An ally deals damage to the target."
  "effects":
  - "name": "Effect"
    "effect": "The ratcrobat makes a [[Free Strike|free strike]] against the target. "

```
