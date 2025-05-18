```ds-statblock
"name": "Wode Elf Lookout"
"ancestry":
- "Fey"
- "Humanoid"
- "Wode Elf"
"roles":
- "Support"
- "Minion"
"level": !!int "1"
"ev": !!int "6"
"stamina": !!int "10"
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
"presence": !!int "1"
"traits":
- "name": "There!"
  "effect": "A wode elf within 5 of the lookout can make a ranged attack as if occupying\
    \ the lookout's space."
- "name": "Masking Glamor"
  "effect": "The lookout immediately [[Hide|hides]] at the end of their turn while in cover\
    \ or concealment, even if they are observed."
"abilities":
- "name": "Longbow"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 8"
  "target": "1 creature or object per minion"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "4 damage"
    "t3": "5 damage "

```
