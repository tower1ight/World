```ds-statblock
"name": "Kobold Centurion"
"ancestry":
- "Humanoid"
- "Kobold"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "20"
"stamina": !!int "50"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1S"
"stability": !!int "2"
"free_strike": !!int "4"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "3"
"reason": !!int "2"
"presence": !!int "2"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the centurion can take 5 damage to end one\
    \ save-ends effect affecting them. This damage can't be reduced in any way."
- "name": "Shield? Shield!"
  "effect": "The centurion has increased Stability by 1 and can act as cover for allies\
    \ when adjacent to an ally who also has this trait."
"abilities":
- "name": "Pilum"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 10"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; 2 [[Weakened|weakened]] (save ends)"
    "t2": "5 damage; 3 [[Weakened|weakened]] (save ends)"
    "t3": "6 damage; 4 [[Weakened|weakened]] (save ends)"
  - "name": "Effect"
    "effect": "Any allies adjacent to a target of this attack can make a [[Free Strike|free strike]]."
  - "name": "3 Malice"
    "effect": "Targets [[Weakened|weakened]] by this attack are now [[Restrained|restrained]] while they are [[Weakened|weakened]]. "
- "name": "Concentrate All Fire on That Hero!"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "One enemy"
  "effects":
  - "name": "Effect"
    "effect": "The target is marked until the start of the centurion's next turn.\
      \ The centurion and each of their allies gain an edge and advantage on attacks\
      \ against targets marked by the centurion."
  - "name": "3+ Malice"
    "effect": "The centurion targets 1 additional enemy for every 3 malice spent. "
- "name": "Testudo!"
  "type": "Triggered Action"
  "keywords":
  - "Weapon"
  "trigger": "A creature attacks the centurion or an ally."
  "distance": "5 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target shifts 2 before the attack damage is resolved. All kobolds\
      \ with *Shield? Shield!* gain increased resistance for this attack. "
- "name": "Firetail Pilum"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "1 × 10 line within 1"
  "target": "All enemies"
  "effects":
  - "name": "Effect"
    "effect": "The centurion makes a pilum attack against each target with advantage.\
      \ Targets take 2 fire damage at the start of each of their turns while [[Weakened|weakened]]. "
- "name": "Boom Pilum!"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "5 cube within 10"
  "target": "All enemies in the cube"
  "effects":
  - "name": "Effect"
    "effect": "The centurion makes a pilum attack against each target with a double\
      \ edge. Each target is then pushed 3. "
- "name": "Are You Not Entertained?!"
  "type": "Villain Action 3"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "10 burst"
  "target": "All enemies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target is [[Taunted|taunted]] (3, save ends). For the rest of the encounter,\
      \ the centurion has Weapon immunity 5. All allies within 10 of the centurion\
      \ can make a [[Free Strike|free strike]]. "

```
