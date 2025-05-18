```ds-statblock
"name": "High Elf Palinode"
"ancestry":
- "Fey"
- "High Elf"
- "Humanoid"
"roles":
- "Defender"
"level": !!int "1"
"ev": !!int "7"
"stamina": !!int "12"
"immunities":
- "magic 2"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "2"
"agility": !!int "0"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Otherworldly Grace"
  "effect": "At the start of their turn, the palinode can turn the duration of one\
    \ save ends effect they suffer from into EoT."
"abilities":
- "name": "Instill Regret"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Magic"
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 8"
  "target": "1 creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 psychic damage; I1 [[Weakened|weakened]] (save ends)"
    "t2": "5 psychic damage; I2 [[Weakened|weakened]] (save ends)"
    "t3": "7 psychic damage; I3 [[Weakened|weakened]] (save ends)"
  - "name": "2 Malice"
    "effect": "The potency of this ability increases by 1. If the target is still\
      \ [[Weakened|weakened]] by this ability at the end of the encounter, they cannot take a respite\
      \ activity during their next respite. "
- "name": "Recall"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 5"
  "target": "2 allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target is teleported to an unoccupied square adjacent to the palinode.\
      \ Then, the palinode and each target gain 5 temporary Stamina. "

```
