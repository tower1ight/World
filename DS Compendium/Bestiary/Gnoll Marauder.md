```ds-statblock
"name": "Gnoll Marauder"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Harrier"
"level": !!int "2"
"ev": !!int "12"
"stamina": !!int "25"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "3"
"might": !!int "1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Death Frenzy"
  "effect": "Whenever an ally within 7 is reduced to 0 Stamina, the marauder moves\
    \ up to their speed and makes a [[Free Strike|free strike]]."
"abilities":
- "name": "Fury Flail"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; A1 [[Bleeding|bleeding]] (save ends)"
    "t2": "5 damage; A2 [[Bleeding|bleeding]] (save ends)"
    "t3": "7 damage; [[Prone|prone]]; A3 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "Shift 2. "
- "name": "Cackletongue"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "--"
  "distance": "Self and 2 burst"
  "target": "Self and all allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target shifts up to their speed. Targets who haven't used a cackletongue\
      \ maneuver on this turn use it immediately at no cost. "

```
