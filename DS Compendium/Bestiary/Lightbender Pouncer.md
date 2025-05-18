```ds-statblock
"name": "[[Lightbender]] Pouncer"
"ancestry":
- "[[Lightbender]]"
- "Monster"
"roles":
- "Harrier"
"level": !!int "3"
"ev": !!int "36"
"stamina": !!int "70"
"immunities": []
"weaknesses": []
"speed": "10"
"size": "2"
"stability": !!int "1"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "-3"
"presence": !!int "-1"
"traits":
- "name": "Avoidance"
  "effect": "The pouncer always treats a save-ends effect as an EoT effect."
"abilities":
- "name": "Pounce"
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
    "t1": "5 damage; 1 [[Prone|prone]]"
    "t2": "9 damage; 2 [[Prone|prone]]"
    "t3": "12 damage; 3 [[Prone|prone]]"
  - "name": "Effect"
    "effect": "The pouncer makes a [[Free Strike|free strike]] against each target they have knocked\
      \ [[Prone|prone]]. "
- "name": "Sparkling Tail Whip"
  "type": "Action"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "2 burst"
  "target": "All enemies and objects in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage; 1 dazzled (save ends)"
    "t2": "4 damage; 2 dazzled (save ends)"
    "t3": "6 damage; 3 dazzled (save ends)"
  - "name": "Effect"
    "effect": "A dazzled creature has a bane on their attacks and can't have line\
      \ of effect to targets who aren't adjacent to them. "
- "name": "Illusory Feint"
  "type": "Maneuver"
  "cost": "5 Malice"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "3 cube within 10"
  "target": "All enemies in the cube"
  "effects":
  - "roll": "REA RR"
    "t1": "[[Dazed]] (save ends)"
    "t2": "[[Dazed]] (EoT)"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "Targets [[Dazed|dazed]] by this ability have a speed of 0 while [[Dazed|dazed]]. If a [[Dazed|dazed]]\
      \ target takes damage or if someone else spends an action to shake the creature\
      \ out of their stupor, the condition is removed. "
- "name": "Striking Afterimage"
  "type": "Triggered Action"
  "keywords":
  - "Magic"
  "trigger": "The [[Lightbender|lightbender]] is damaged by an attack"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The [[Lightbender|lightbender]] halves the damage, doesn't suffer any associated effect,\
      \ and [[Teleport|teleports]] 5 squares. The pouncer makes a [[Free Strike|free strike]] if they [[Teleport|teleport]]\
      \ into a space adjacent to an enemy. "

```
