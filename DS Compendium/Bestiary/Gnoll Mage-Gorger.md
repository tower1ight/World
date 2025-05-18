```ds-statblock
"name": "Gnoll Mage-Gorger"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Hexer"
- "Minion"
"level": !!int "2"
"ev": !!int "4"
"stamina": !!int "8"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "2"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "-1"
"presence": !!int "0"
"traits":
- "name": "Death Frenzy"
  "effect": "Whenever an ally within 5 is reduced to 0 Stamina, the mage-gorger moves\
    \ up to their speed and makes a [[Free Strike|free strike]]."
"abilities":
- "name": "Wizard Ripper"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Melee"
  "distance": "Melee 1"
  "target": "1 creature or object per minion"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 acid damage"
    "t2": "3 cold damage"
    "t3": "4 lightning damage; target can't use magic abilities (EoT)"
  - "name": "Effect"
    "effect": "The target has a bane on their next resistance roll until the start\
      \ of the mage-gorger's next turn. "

```
