```ds-statblock
"name": "Gnoll Wildling"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Harrier"
- "Minion"
"level": !!int "2"
"ev": !!int "5"
"stamina": !!int "10"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "2"
"might": !!int "1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "-2"
"traits":
- "name": "Death Frenzy"
  "effect": "Whenever an ally within 7 is reduced to 0 Stamina, the wildling moves\
    \ up to their speed and makes a [[Free Strike|free strike]]."
"abilities":
- "name": "Flail"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object per minion"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "3 damage"
    "t3": "4 damage; wildling takes a [[Free Strike|free strike]] on a creature adjacent to the target "

```
