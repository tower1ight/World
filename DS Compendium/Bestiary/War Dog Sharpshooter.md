```ds-statblock
"name": "War Dog Sharpshooter"
"ancestry":
- "Humanoid"
- "War Dog"
"roles":
- "Artillery"
- "Minion"
"level": !!int "1"
"ev": !!int "4"
"stamina": !!int "8"
"immunities": []
"weaknesses": []
"speed": "7"
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
  "effect": "When the sharpshooter dies, they explode, dealing 1d6 damage to each\
    \ adjacent enemy."
"abilities":
- "name": "Bolt Launcher"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 5"
  "target": "One creature or object per minion"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "3 damage"
    "t3": "4 damage"
  - "name": "Effect"
    "effect": "This ability ignores cover and concealment. "

```
