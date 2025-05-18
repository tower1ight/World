```ds-statblock
"name": "[[Basilisk]] Tonguesnapper"
"ancestry":
- "[[Basilisk]]"
- "Monster"
"roles":
- "HEXER"
"level": !!int "1"
"ev": !!int "26"
"stamina": !!int "50"
"immunities":
- "Poison 5"
"weaknesses": []
"speed": "8"
"size": "2"
"stability": !!int "2"
"free_strike": !!int "4"
"might": !!int "1"
"intuition": !!int "-1"
"agility": !!int "2"
"reason": !!int "-3"
"presence": !!int "-1"
"traits":
- "name": "Petrifying Fumes"
  "effect": "A creature that starts their turn adjacent to the tonguesnapper is M2\
    \ [[Slowed|slowed]] (save ends)."
"abilities":
- "name": "Prehensile Tongue"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 3"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "6 acid damage; pull 1"
    "t2": "8 acid damage; pull 2"
    "t3": "12 acid damage; pull 3"
  - "name": "Effect"
    "effect": "This attack can pull targets [[Restrained|restrained]] by Petrifying Eye Beams."
  - "name": "3 Malice"
    "effect": "The tonguesnapper targets two additional creatures or objects. "
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
    "effect": "The tonguesnapper targets the first unobstructed creature in each column\
      \ of the area. Each target magically begins to turn to stone. An already [[Slowed|slowed]]\
      \ target has a bane on resisting the roll. A creature [[Restrained|restrained]] by this ability\
      \ or a creature adjacent to them can use an action to cut the encroaching stone\
      \ from their body, taking 8 damage which can't be reduced in any way and ending\
      \ the effect."
- "name": "Wink"
  "type": "Action"
  "cost": "2 Malice"
  "keywords":
  - "Attack"
  - "Melee"
  - "Magic"
  - "Ranged"
  "distance": "Melee 1 or Ranged 10"
  "target": "1 creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "6 corruption damage; R1 [[Dazed|dazed]] (save ends)"
    "t2": "8 corruption damage; R2 [[Dazed|dazed]] (save ends)"
    "t3": "12 corruption damage; R3 [[Dazed|dazed]] and [[Slowed|slowed]] (save ends)"
  - "name": "Effect"
    "effect": "A creature [[Dazed|dazed]] by this ability can't benefit from edges or concealment\
      \ until the condition ends. "
- "name": "Neurotoxin Splash"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "The tonguesnapper takes Weapon damage."
  "distance": "2 burst"
  "target": "All enemies in the burst"

```
