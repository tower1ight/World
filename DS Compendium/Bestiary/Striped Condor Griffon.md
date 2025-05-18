```ds-statblock
"name": "Striped Condor [[Griffon]]"
"ancestry":
- "Animal"
- "[[Griffon]]"
"roles":
- "Brute"
"level": !!int "2"
"ev": !!int "36"
"stamina": !!int "80"
"immunities": []
"weaknesses": []
"speed": "7 ([[Fly|fly]])"
"size": "3"
"stability": !!int "5"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "-1"
"presence": !!int "1"
"traits":
- "name": "Beast of Prey"
  "effect": "Creatures have a double bane when using the [[Escape Grab]] maneuver to escape\
    \ the [[Griffon|griffon]]'s [[Grab|grab]]."
- "name": "Steady"
  "effect": "Creatures have a bane on power rolls that could knock the [[Griffon|griffon]] [[Prone|prone]]."
- "name": "Banded Predator"
  "effect": "The [[Griffon|griffon]] is hidden whenever they have cover or concealment."
"abilities":
- "name": "Violent Thrashing"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Reach 2"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; push 1"
    "t2": "9 damage; one target is pushed 2; other target is vertically pushed 2"
    "t3": "12 damage; one target is pushed 2 and [[Prone|prone]]; other target is vertically\
      \ pushed 3 "
- "name": "Bound Ahead"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "--"
  "distance": "Self (while [[Grounded|grounded]])"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The [[Griffon|griffon]] shifts up to their speed in a straight line. Each enemy\
      \ within their reach during this movement can choose to either take 5 damage\
      \ or be knocked [[Prone|prone]]. "
- "name": "Wing Buffet"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "5 × 3 line within 1"
  "target": "All creatures and objects"
  "effects":
  - "roll": "MGT RR"
    "t1": "Vertical push 5"
    "t2": "Push 4"
    "t3": "Push 3 "
- "name": "Circle and Strike"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The [[Griffon|griffon]] flies above a creature on the ground within 10"
  "distance": "Self"
  "target": "Triggering creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "Push 3"
    "t2": "A2 [[Grabbed|grabbed]]"
    "t3": "5 damage; A3 [[Grabbed|grabbed]]"
  - "name": "Effect"
    "effect": "The [[Griffon|griffon]] falls down upon the target, taking no damage from [[Falling|falling]].\
      \ A creature who is [[Grabbed|grabbed]] by the [[Griffon|griffon]] is [[Prone|prone]] and can't stand until they\
      \ are no longer [[Grabbed|grabbed]]. "

```
