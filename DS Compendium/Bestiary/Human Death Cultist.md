```ds-statblock
"name": "[[Human]] Death Cultist"
"ancestry":
- "[[Human]]"
- "Humanoid"
"roles":
- "Support"
"level": !!int "2"
"ev": !!int "16"
"stamina": !!int "40"
"immunities":
- "Magic 2"
- "Psionic 2"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "4"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "2"
"traits":
- "name": "Supernatural Insight"
  "effect": "The death cultist can target supernatural creatures and objects within\
    \ 5 squares, even if they don't have line of effect."
"abilities":
- "name": "Death Scythe"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 10"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 corruption damage; I1 [[Weakened|weakened]] (save ends)"
    "t2": "7 corruption damage; I2 [[Weakened|weakened]] (save ends)"
    "t3": "10 corruption damage; I3 [[Weakened|weakened]] (save ends)"
  - "name": "2 Malice"
    "effect": "The death cultist regains Stamina equal to half the damage dealt by\
      \ this ability. "
- "name": "Rise, My Minions"
  "type": "Maneuver"
  "cost": "1 Malice per minion"
  "keywords":
  - "Area"
  "distance": "5 burst"
  "target": "One or more dead minions"
  "effects":
  - "name": "Special"
    "effect": "Each target must have died during this encounter"
  - "name": "Effect"
    "effect": "Each target revives with their full Stamina. They immediately die at\
      \ the end of the encounter or if the death cultist is killed. A target can be\
      \ revived multiple times by this ability. "

```
