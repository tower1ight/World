```ds-statblock
"name": "Lizardfolk Bloodeye"
"ancestry":
- "Humanoid"
- "Lizardfolk"
"roles":
- "Hexer"
"level": !!int "1"
"ev": !!int "11"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "5 (swim)"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "3"
"might": !!int "1"
"intuition": !!int "2"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "0"
"traits":
- "name": "Reptilian Escape"
  "effect": "While the bloodeye still has a tail, whenever the bloodeye is [[Grabbed|grabbed]],\
    \ [[Slowed|slowed]], [[Weakened|weakened]], or knocked [[Prone|prone]], the bloodeye can lose their tail to immediately\
    \ end the effect and shift 2."
"abilities":
- "name": "Bola Knock"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 5"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage"
    "t2": "5 damage; A1 [[Restrained|restrained]] (save ends)"
    "t3": "7 damage; A2 [[Restrained|restrained]] (save ends) "
- "name": "Bloodshot"
  "type": "Action"
  "cost": "2 Malice"
  "keywords":
  - "Attack"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "1 creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 acid damage; M1 target can't establish line of effect beyond 3 squares\
      \ (save ends)"
    "t2": "5 acid damage; M2 target can't establish line of effect beyond 2 squares\
      \ (save ends)"
    "t3": "7 acid damage; M3 target can't establish line of effect beyond 1 square\
      \ (save ends) "

```
