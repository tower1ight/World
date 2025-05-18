```ds-statblock
"name": "Ogre Juggernaut"
"ancestry":
- "Giant"
- "Ogre"
"roles":
- "Harrier"
"level": !!int "2"
"ev": !!int "32"
"stamina": !!int "70"
"immunities": []
"weaknesses": []
"speed": "6"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "-1"
"presence": !!int "-1"
"traits":
- "name": "Destructive Path"
  "effect": "The juggernaut automatically destroys unattended, [[Mundane|mundane]] size 1 objects\
    \ in their path during their movement. They can break through any [[Mundane|mundane]] wall\
    \ made of wood, stone, or a similarly sturdy material in this way, so long as\
    \ the wall is no more than 1 square thick."
- "name": "Defiant Anger"
  "effect": "The juggernaut has Weapon immunity 2 while they are winded."
"abilities":
- "name": "Pitchfork Catapult"
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
    "t1": "5 damage; A1 vertical slide 2"
    "t2": "8 damage; A2 vertical push 3"
    "t3": "11 damage; A3 vertical slide 5"
  - "name": "1 Malice"
    "effect": "Each target is M2 [[Bleeding|bleeding]] (save ends). "
- "name": "Earth Breaking [[Jump]]"
  "type": "Action"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "3 burst"
  "target": "All creatures in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; M1 [[Prone|prone]]"
    "t2": "4 damage; push 2; M2 [[Prone|prone]]"
    "t3": "5 damage; push 4; M3 [[Prone|prone]] "
  - "name": "Effect"
    "effect": "The juggernaut leaps up to 6 squares before making the attack. "
- "name": "Horrible Bellow"
  "type": "Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "3 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "INU RR"
    "t1": "[[Frightened]] (save ends)"
    "t2": "[[Frightened]] (EoT)"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "Ogres have **advantage** on attacks against creatures [[Frightened|frightened]] by\
      \ this ability. "
- "name": "Hrraaaaaagh!"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The juggernaut takes damage."
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "name": "Effect"
    "effect": "The juggernaut moves up to their speed and makes a [[Free Strike|free strike]]. "

```
