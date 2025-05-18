```ds-statblock
"name": "Lizardfolk Deathrex"
"ancestry":
- "Humanoid"
- "Lizardfolk"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "36"
"stamina": !!int "60"
"immunities": []
"weaknesses": []
"speed": "5 (climb, swim)"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "3"
"intuition": !!int "1"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "2"
"traits":
- "name": "Rex Reptilian Escape"
  "effect": "While the deathrex still has a tail, whenever the deathrex is inflicted\
    \ with an EoT or save ends effect, the deathrex can lose their tail to immediately\
    \ end the effect and shift 2."
"abilities":
- "name": "Ripper Spear"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 3"
  "target": "3 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage; pull 1; A2 [[Bleeding|bleeding]] (save ends)"
    "t2": "7 damage; pull 1; A3 [[Bleeding|bleeding]] (save ends)"
    "t3": "10 damage; pull 2; A4 [[Bleeding|bleeding]] (save ends)"
  - "name": "1 Malice"
    "effect": "One target that is adjacent to the deathrex is [[Grabbed|grabbed]] by the deathrex's\
      \ mouth. "
- "name": "Death Roll"
  "type": "Action"
  "cost": "3 Malice"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 [[Grabbed|grabbed]] creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; M2 [[Dazed|dazed]] (save ends)"
    "t2": "10 damage; M3 [[Dazed|dazed]] (save ends)"
    "t3": "15 damage; M4 [[Dazed|dazed]] (save ends)"
  - "name": "Effect"
    "effect": "The target is released from the [[Grab|grab]] and slides 5. "
- "name": "Trundle"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The deathrex moves up to their speed. The deathrex can make a free\
      \ strike on each creature that makes an opportunity attack against them during\
      \ this movement. "
- "name": "Swat The [[Fly]]"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The target moves or shifts away from the deathrex."
  "distance": "Melee 1"
  "target": "1 adjacent creature or object"
  "effects":
  - "name": "Effect"
    "effect": "Slide 5. "
- "name": "Snack Attack"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  "distance": "Self and 10 burst"
  "target": "Self and all allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target moves up to their speed and makes a [[Free Strike|free strike]]. A target\
      \ receives temporary Stamina equal to the amount of damage they dealt during\
      \ this action. "
- "name": "Shed Some Skin"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The deathrex shifts up to their speed, leaving behind a skin shed duplicate\
      \ in the space that they started in. The duplicate has 10 Stamina, has no villain\
      \ actions, shares the rest of the deathrex's characteristics, and takes their\
      \ turn at the same time as the deathrex. "
- "name": "Thresher Thrasher"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  "distance": "Self and 10 burst"
  "target": "Self and all allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target moves up to their speed. Until the end of the encounter,\
      \ when a creature enters or starts their turn adjacent to a target, the target\
      \ can make a [[Free Strike|free strike]] against them. "

```
