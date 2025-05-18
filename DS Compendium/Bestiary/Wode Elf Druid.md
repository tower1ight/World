```ds-statblock
"name": "Wode Elf Druid"
"ancestry":
- "Fey"
- "Humanoid"
- "Wode Elf"
"roles":
- "Controller"
"level": !!int "2"
"ev": !!int "13"
"stamina": !!int "25"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "3"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "2"
"traits":
- "name": "Masking Glamor"
  "effect": "The druid immediately [[Hide|hides]] at the end of their turn while in cover or\
    \ concealment, even if they are observed."
"abilities":
- "name": "Entangling Vines"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Magic"
  - "Ranged"
  "distance": "3 cube within 10"
  "target": "All enemies in the cube"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; pull 1; M1 [[Slowed|slowed]] (save ends)"
    "t2": "5 damage; pull 3; M2 [[Slowed|slowed]] (save ends)"
    "t3": "7 damage; pull 5; M3 [[Slowed|slowed]] (save ends)"
  - "name": "Effect"
    "effect": "A creature [[Slowed|slowed]] by this ability can't [[Search For Hidden Creatures|search for hidden creatures]]\
      \ until the condition ends."
  - "name": "3 Malice"
    "effect": "The area of the cube and the potency of the effect both increase by\
      \ 1. "
- "name": "The Wode Protects Us"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Magic"
  "distance": "Self and Ranged 5"
  "target": "Self and 3 allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target [[Teleport|teleports]] to a square within 10 that has cover or concealment\
      \ from all enemies. "

```
