```ds-statblock
"name": "Kobold Adeptus"
"ancestry":
- "Humanoid"
- "Kobold"
"roles":
- "Artillery"
"level": !!int "1"
"ev": !!int "8"
"stamina": !!int "12"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "1"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "2"
"presence": !!int "0"
"traits":
- "name": "Shield? Shield!"
  "effect": "The adeptus has increased Stability by 1 and can act as cover for allies\
    \ when adjacent to an ally who also has this trait."
"abilities":
- "name": "Shocking Bolt"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 lightning damage"
    "t2": "5 lightning damage"
    "t3": "6 lightning damage"
  - "name": "Effect"
    "effect": "The adeptus has an edge on the attack if the target is adjacent to\
      \ another enemy. All enemies adjacent to the target take 1 lightning damage. "
- "name": "Arcane Telum"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 15"
  "target": "3 creatures or objects"
  "effects":
  - "roll": "2d10 + 1"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage"
  - "name": "Effect"
    "effect": "This attack ignores all banes and hindrances. "

```
