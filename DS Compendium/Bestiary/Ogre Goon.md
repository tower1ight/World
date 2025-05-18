```ds-statblock
"name": "Ogre Goon"
"ancestry":
- "Giant"
- "Ogre"
"roles":
- "Brute"
"level": !!int "2"
"ev": !!int "36"
"stamina": !!int "80"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "2"
"stability": !!int "4"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "0"
"reason": !!int "-1"
"presence": !!int "-1"
"traits":
- "name": "Defiant Anger"
  "effect": "The goon has Weapon immunity 2 while they are winded."
"abilities":
- "name": "Club Swing"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; push 2"
    "t2": "9 damage; push 4"
    "t3": "12 damage; push 6; [[Prone|prone]]"
  - "name": "Effect"
    "effect": "This attack deals **additional damage** to each creature and object\
      \ that takes damage from any [[Forced Movement|forced movement]] it causes. "
- "name": "Grabby Hand"
  "type": "Maneuver"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage"
    "t2": "9 damage; [[Grabbed|grabbed]]"
    "t3": "12 damage; [[Grabbed|grabbed]]"
  - "name": "Effect"
    "effect": "The goon can only have one target [[Grabbed|grabbed]] at a time."
  - "name": "1 Malice"
    "effect": "The target has a bane on escaping the [[Grab|grab]] while the goon crushes the\
      \ target in their hand. "
- "name": "People Bowling"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "6 × 1 Line (while grabbing a Size 1 creature or object)"
  "target": "All creatures and objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage"
    "t2": "4 damage"
    "t3": "6 damage; [[Prone|prone]] "
  - "name": "Effect"
    "effect": "The goon hurls what's in their hand down the line and rolls power.\
      \ The hurled creature or object counts as a target and lands in the last square\
      \ of the line (or nearest unoccupied square of the goon's choice). "
- "name": "Swat The [[Fly]]"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The target moves or shifts away from the goon."
  "distance": "Melee 1"
  "target": "1 adjacent creature or object"
  "effects":
  - "name": "Effect"
    "effect": "Slide 5. "

```
