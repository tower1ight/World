```ds-statblock
"name": "[[Dwarf]] Trapper"
"ancestry":
- "[[Dwarf]]"
- "Humanoid"
"roles":
- "Harrier"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "36"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "2"
"free_strike": !!int "3"
"might": !!int "0"
"intuition": !!int "1"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits": []
"abilities":
- "name": "Concussive Bolts"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 10"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; push 2"
    "t2": "5 damage; push 4"
    "t3": "7 damage; push 6"
  - "name": "Effect"
    "effect": "A target [[Restrained|restrained]] by a [[Dwarf|dwarf]] can be pushed by this attack. "
- "name": "Steam Powered Snare"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "3 cube within 5"
  "target": "All enemies in the cube"
  "effects":
  - "roll": "MGT RR"
    "t1": "4 damage; [[Restrained|restrained]] (EoT)"
    "t2": "3 damage; [[Slowed|slowed]] (EoT)"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "The snare remains until the end of the encounter. An enemy that moves\
      \ into an affected square for the first time on their turn must roll resistance."

```
