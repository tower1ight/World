```ds-statblock
"name": "Basilisk"
"ancestry":
- "Basilisk"
- "Monster"
"roles":
- "BRUTE"
"level": !!int "1"
"ev": !!int "32"
"stamina": !!int "70"
"immunities":
- "Poison 5"
"weaknesses": []
"speed": "8"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "-1"
"agility": !!int "0"
"reason": !!int "-3"
"presence": !!int "-1"
"traits":
- "name": "Calcifying Presence"
  "effect": "The area within 3 squares of the basilisk is considered [[Difficult Terrain|difficult terrain]]\
    \ for enemies."
"abilities":
- "name": "Noxious Bite"
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
    "t1": "5 poison damage"
    "t2": "8 poison damage"
    "t3": "11 poison damage"
  - "name": "Effect"
    "effect": "This attack has an edge against targets that the basilisk has previously\
      \ dealt poison damage to. "
- "name": "Petrifying Eye Beams"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 5 × 2 line within 1"
  "target": "Special"
  "effects":
  - "roll": "MGT RR"
    "t1": "[[Restrained]] (save ends)"
    "t2": "[[Slowed]] (save ends)"
    "t3": "[[Slowed]] (EoT)"
  - "name": "Effect"
    "effect": "The basilisk targets the first unobstructed creature in each column\
      \ of the area. Each target magically begins to turn to stone. An already [[Slowed|slowed]]\
      \ target has a bane on resisting the roll. A creature [[Restrained|restrained]] by this ability\
      \ or a creature adjacent to them can use an action to cut the encroaching stone\
      \ from their body, taking 8 damage which can't be reduced in any way and ending\
      \ the effect."
- "name": "Poison Fumes"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "3 cube within 1"
  "target": "All creatures in the cube"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 poison damage; M1 [[Weakened|weakened]] (save ends)"
    "t2": "6 poison damage; M2 [[Weakened|weakened]] and [[Slowed|slowed]] (save ends)"
    "t3": "9 poison damage; M3 [[Weakened|weakened]] and [[Slowed|slowed]] (save ends) "
- "name": "Lash Out"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The basilisk takes Weapon damage."
  "distance": "1 burst"
  "target": "All enemies in the burst"

```
