```ds-statblock
"name": "War Dog Crucibite"
"ancestry":
- "Humanoid"
- "War Dog"
"roles":
- "Artillery"
"level": !!int "1"
"ev": !!int "10"
"stamina": !!int "15"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits":
- "name": "Loyalty Collar"
  "effect": "When the crucibite dies, they explode, dealing 1d6 damage to each adjacent\
    \ enemy."
"abilities":
- "name": "Flamebelcher"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "5 × 1 line within 1"
  "target": "All creatures and objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 fire damage"
    "t2": "5 fire damage"
    "t3": "6 fire damage"
  - "name": "Effect"
    "effect": "The area is covered in sticky fire until the start of the crucibite's\
      \ next turn. Whenever a creature enters the area for the first time in a round\
      \ or starts their turn there, they take 2 fire damage."
  - "name": "3 Malice"
    "effect": "The area increases to a 10 × 1 line, and if any ally of the crucibite\
      \ is in the area when it is created, the crucibite has **edge** on the ability. "
- "name": "Posthumous Promotion"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "One war dog with a loyalty collar"
  "effects":
  - "name": "Effect"
    "effect": "The target's loyalty collar detonates, killing them instantly. "

```
