```ds-statblock
"name": "Griffon"
"ancestry":
- "Animal"
- "Griffon"
"roles":
- "Mount"
"level": !!int "2"
"ev": !!int "32"
"stamina": !!int "70"
"immunities": []
"weaknesses": []
"speed": "9 ([[Fly|fly]])"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "-1"
"presence": !!int "2"
"traits":
- "name": "Beast of Prey"
  "effect": "Creatures have a double bane on escaping the griffon's [[Grab|grab]]."
- "name": "Steady"
  "effect": "Creatures have a bane on power rolls that could knock the griffon or\
    \ their rider [[Prone|prone]]."
"abilities":
- "name": "Claw Swipes"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; shift 1"
    "t2": "8 damage; shift 2"
    "t3": "11 damage; shift 3"
  - "name": "Effect"
    "effect": "If this ability is used while charging, the griffon grapples one of\
      \ the targets. "
- "name": "Crack the Earth"
  "type": "Maneuver"
  "keywords":
  - "Area"
  - "Ranged"
  "distance": "3 cube within 8 (while flying and grappling a creature or object)"
  "target": "All enemies"
  "t1": "2 damage; A1 push 2"
  "t2": "3 damage; A2 push 3"
  "t3": "4 damage; A3 push 4 and [[Prone|prone]] "
  "effects":
  - "name": "Effect"
    "effect": "The griffon flies up to half their speed towards the ground and then\
      \ sends the creature or object they've grappled hurtling towards the affected\
      \ area."
- "name": "Wing Buffet"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "4 × 2 line within 1"
  "target": "All creatures and objects"
  "effects":
  - "roll": "MGT RR"
    "t1": "Vertical push 4"
    "t2": "Push 3"
    "t3": "Push 2 "
- "name": "Juke"
  "type": "Triggered Action"
  "cost": "1 Malice"
  "keywords":
  - "--"
  "trigger": "The griffon takes damage"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The griffon halves the damage, doesn't suffer any effect associated\
      \ with it, and shifts 2 squares. "

```
