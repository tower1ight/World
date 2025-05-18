```ds-statblock
"name": "Lizardfolk Terrorsoar"
"ancestry":
- "Humanoid"
- "Lizardfolk"
"roles":
- "Harrier"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "30"
"immunities": []
"weaknesses": []
"speed": "7 (swim)"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Glider"
  "effect": "The terrorsoar adds the flying keyword to their movement until the end\
    \ of their next turn whenever they move at least 2 squares along the ground or\
    \ fall at least 2 squares."
- "name": "Reptilian Escape"
  "effect": "While the terrorsoar still has a tail, whenever the terrorsoar is [[Grabbed|grabbed]],\
    \ [[Slowed|slowed]], [[Weakened|weakened]], or knocked [[Prone|prone]], the terrorsoar can lose their tail to immediately\
    \ end the effect and shift 2."
"abilities":
- "name": "Glaive Rush"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage"
    "t2": "5 damage"
    "t3": "7 damage; [[Prone|prone]]"
  - "name": "Effect"
    "effect": "The terrorsoar can shift 4 after using this ability if they are flying. "
- "name": "Poison Blowdart"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 5"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage; M1 [[Weakened|weakened]] (save ends)"
    "t2": "5 damage; M2 [[Weakened|weakened]] (save ends)"
    "t3": "6 damage; M3 [[Weakened|weakened]] (save ends)"
  - "name": "Effect"
    "effect": "A creature that ends their turn adjacent to a creature or object [[Weakened|weakened]]\
      \ by this ability is [[Weakened|weakened]] (EoT). "

```
