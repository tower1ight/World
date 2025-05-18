```ds-statblock
"name": "War Spider"
"ancestry":
- "Animal"
- "Goblin"
"roles":
- "Mount"
"level": !!int "1"
"ev": !!int "28"
"stamina": !!int "60"
"immunities": []
"weaknesses": []
"speed": "7 (climb)"
"size": "3"
"stability": !!int "2"
"free_strike": !!int "4"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "-4"
"presence": !!int "-3"
"traits":
- "name": "[[Ride]] Launcher"
  "effect": "An ally who leaps off the back of the spider can [[Jump|jump]] up to 6 squares\
    \ without a test, and takes no damage if they fall during the [[Jump|jump]]. After the\
    \ [[Jump|jump]], the first melee attack an ally makes on the same turn gains an edge."
- "name": "Wide Back"
  "effect": "Two of the spider's size 1 allies can occupy the same space while riding\
    \ the spider."
"abilities":
- "name": "Bite"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 poison damage; M1 [[Weakened|weakened]] (save ends)"
    "t2": "7 poison damage; M2 [[Weakened|weakened]] (save ends)"
    "t3": "10 poison damage; M3 [[Weakened|weakened]] (save ends) "
- "name": "Leg Blade"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 damage"
    "t2": "7 damage"
    "t3": "10 damage "
- "name": "Trample"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The spider shifts up to their speed and makes a Leg Blade attack against\
      \ each creature who comes within 1 of the spider during the move. The spider\
      \ makes one power roll against all targets. "
- "name": "Web"
  "type": "Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "3 cube within 1"
  "target": "All creatures in the cube"
  "effects":
  - "roll": "AGL RR"
    "t1": "[[Restrained]] (AGL ends)"
    "t2": "[[Restrained]] (EoT)"
    "t3": "No effect "

```
