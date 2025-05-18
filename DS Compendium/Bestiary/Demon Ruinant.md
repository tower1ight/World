```ds-statblock
"name": "Demon Ruinant"
"ancestry":
- "Demon"
- "Planar"
"roles":
- "HARRIER"
"level": !!int "1"
"ev": !!int "10"
"stamina": !!int "20"
"immunities": []
"weaknesses":
- "Holy 3"
"speed": "6"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Lethe"
  "effect": "While winded, the ruinant has an edge on attacks, and attacks have an\
    \ edge against them."
- "name": "Soulsight"
  "effect": "Each creature within 2 of the ruinant can't be hidden from them."
"abilities":
- "name": "Bloodletting Claws"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage; M1 [[Bleeding|bleeding]] (save ends)"
    "t3": "6 damage; M2 [[Bleeding|bleeding]] (save ends) "
- "name": "Salt Wounds"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "Three creatures without full Stamina"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 corruption damage"
    "t2": "5 corruption damage"
    "t3": "6 corruption damage "

```
