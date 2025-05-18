```ds-statblock
"name": "Fossil Cryptic"
"ancestry":
- "Elemental"
"roles":
- "Solo"
"level": !!int "2"
"ev": !!int "76"
"stamina": !!int "180"
"immunities":
- "weapon 5"
"weaknesses": []
"speed": "8 ([[Burrow|burrow]])"
"size": "1L"
"stability": !!int "3"
"free_strike": !!int "5"
"might": !!int "3"
"intuition": !!int "1"
"agility": !!int "2"
"reason": !!int "1"
"presence": !!int "0"
"traits":
- "name": "Solo Monster"
  "effect": "- **Solo Turns**: The cryptic takes two turns each round. They can use\
    \ two actions on each of their turns and can take each turn after any enemy's\
    \ turn. While [[Dazed|dazed]], the cryptic can take one action and one maneuver per turn.\
    \ - **End Effect**: At the end of their turn, the cryptic can take 5 damage to\
    \ end one save ends effect affecting them. This damage can't be reduced in any\
    \ way."
- "name": "Churning Trunk"
  "effect": "The cryptic emits a 1-square aura of swirling debris that obscures their\
    \ form. Any enemy who enters the aura for the first time in a round or starts\
    \ their turn there takes 5 damage."
- "name": "Seismic Step"
  "effect": "The cryptic ignores [[Difficult Terrain|difficult terrain]]. Additionally, they have line of\
    \ effect to concealed creatures touching the ground."
"abilities":
- "name": "Sand Slam"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; A2 [[Prone|prone]]"
    "t2": "9 damage; A3 [[Prone|prone]] and can't stand (EoT)"
    "t3": "12 damage; A4 [[Prone|prone]] and can't stand (save ends)"
  - "name": "Effect"
    "effect": "Each enemy within 1 square of the target takes 2 damage. "
- "name": "Stone Bone Storm"
  "type": "Action"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "6 × 1 line within 1"
  "target": "Each enemy in the line"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; M2 push 2"
    "t2": "3 damage; M3 [[Prone|prone]]"
    "t3": "4 damage; M4 [[Prone|prone]]"
  - "name": "Effect"
    "effect": "The cryptic reforms their body and appears in an unoccupied space within\
      \ the line. "
- "name": "Shatterstone"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "Area"
  "distance": "4 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; push 2"
    "t2": "3 damage; push 3; [[Prone|prone]]"
    "t3": "4 damage; push 4; [[Prone|prone]] "
  - "name": "Effect"
    "effect": "The cryptic [[Burrow|burrows]] up to half their speed, then creates the burst\
      \ when they breach the surface."
- "name": "Stoneshift"
  "type": "Maneuver"
  "keywords":
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 5"
  "target": "One creature or object on the ground"
  "effects":
  - "roll": "AGL RR"
    "t1": "Slide 3"
    "t2": "Slide 2"
    "t3": "Slide 1"
  - "name": "2 Malice"
    "effect": "The distance of the slide is doubled. "
- "name": "Dissipate"
  "type": "Triggered Action"
  "cost": "1 Malice"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "trigger": "The cryptic takes damage"
  "effects":
  - "name": "Effect"
    "effect": "The cryptic halves the damage, doesn't suffer any additional effect\
      \ associated with it, and shifts up to 3 squares. "
- "name": "First Warning Quake"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "5 burst"
  "target": "Each enemy on the ground in the burst"
  "effects":
  - "roll": "MGT RR"
    "t1": "The target is [[Prone|prone]] and can't stand (EoT)"
    "t2": "[[Prone]]"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "The area becomes [[Difficult Terrain|difficult terrain]]. "
- "name": "Final Warning Fissure"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "5 burst"
  "target": "Each enemy on the ground in the burst"
  "effects":
  - "roll": "AGL RR"
    "t1": "4 damage; [[Prone|prone]]"
    "t2": "2 damage"
    "t3": "The target moves to the nearest unoccupied space outside the area."
  - "name": "Effect"
    "effect": "The area drops 2 squares. Each enemy in the area falls, while all allies\
      \ of the fossil cryptic drop safely. The affected area then becomes difficult\
      \ terrain. "
- "name": "No Escape"
  "type": "Villain Action 3"
  "keywords":
  - "Ranged"
  "distance": "Ranged 10"
  "target": "Two creatures or objects on the ground"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; vertical slide 2"
    "t2": "3 damage; vertical slide 4"
    "t3": "4 damage; the target is [[Restrained|restrained]] against the ceiling (save ends)"
  - "name": "Effect"
    "effect": "The cryptic makes an initial attack that calls down stone pillars from\
      \ the ceiling."
  - "name": "Effect"
    "effect": "The cryptic makes a final attack that raises stone pillars from the\
      \ floor."

```
