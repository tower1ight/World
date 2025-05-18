```ds-statblock
"name": "Bugbear Roughneck"
"ancestry":
- "Bugbear"
- "Goblin"
- "Humanoid"
"roles":
- "BRUTE"
"level": !!int "2"
"ev": !!int "36"
"stamina": !!int "80"
"immunities": []
"weaknesses": []
"speed": "6"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits": []
"abilities":
- "name": "Haymaker"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage"
    "t2": "9 damage; one target is [[Grabbed|grabbed]]; one target gets push 2"
    "t3": "12 damage; one target is [[Grabbed|grabbed]]; one target gets vertical push 3"
  - "name": "5 Malice"
    "effect": "The distance becomes 1 Burst, the Attack keyword is replaced with Area,\
      \ and the roughneck targets all enemies instead. "
- "name": "Leaping Fury"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; M1 [[Prone|prone]]"
    "t2": "9 damage; M2 [[Prone|prone]]"
    "t3": "12 damage; M3 [[Prone|prone]]"
  - "name": "Effect"
    "effect": "The roughneck leaps 5 to an unoccupied space adjacent to the target\
      \ before making the attack. "
- "name": "Drag Through Hell"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Melee"
  "distance": "Melee 1"
  "target": "1 creature or object [[Grabbed|grabbed]] by the roughneck"
  "effects":
  - "name": "Effect"
    "effect": "The roughneck moves up to their speed, dragging the target across the\
      \ ground. The target takes 1 damage for each square they were dragged through\
      \ before being released [[Prone|prone]]. Each square the target was dragged through becomes\
      \ [[Difficult Terrain|difficult terrain]]. "
- "name": "Throw"
  "type": "Maneuver"
  "keywords":
  - "Attack"
  - "Melee"
  "distance": "Melee 1"
  "target": "1 creature or object [[Grabbed|grabbed]] by the roughneck"
  "effects":
  - "name": "Effect"
    "effect": "Vertical push 5. Ally targets don't take damage from being force moved. "
- "name": "Catcher"
  "type": "Free Triggered Action"
  "keywords":
  - "--"
  "distance": "Melee 1"
  "target": "1 size 1 creature or object"
  "trigger": "The target is force moved into a square adjacent to the roughneck."
  "effects":
  - "name": "Effect"
    "effect": "The target is [[Grabbed|grabbed]] by the roughneck. "
- "name": "Flying Sawblade"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "trigger": "The roughneck is vertically moved by another creature."
  "effects":
  - "name": "Effect"
    "effect": "The roughneck uses their Haymaker ability against a creature or object\
      \ within reach at the end of the movement."
"weapon_immunity": "3"

```
