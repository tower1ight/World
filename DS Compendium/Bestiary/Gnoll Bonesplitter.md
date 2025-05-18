```ds-statblock
"name": "Gnoll Bonesplitter"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Brute"
"level": !!int "2"
"ev": !!int "15"
"stamina": !!int "35"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1L"
"stability": !!int "1"
"free_strike": !!int "4"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Death Frenzy"
  "effect": "Whenever an ally within 5 is reduced to 0 Stamina, the bonesplitter moves\
    \ up to their speed and makes a [[Free Strike|free strike]]."
"abilities":
- "name": "Three-Tail Flail"
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
    "t1": "4 damage; push 2"
    "t2": "7 damage; [[Grabbed|grabbed]]; M2 target has a bane on attempts to [[Escape Grab|escape grab]]"
    "t3": "10 damage; [[Grabbed|grabbed]]; M3 target has a bane on attempts to [[Escape Grab|escape grab]]"
  - "name": "Effect"
    "effect": "The bonesplitter can't use three-tail flail on another target while\
      \ the current target is [[Grabbed|grabbed]]. "
- "name": "Cackletongue"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "--"
  "distance": "Self and 2 burst"
  "target": "Self and all allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target makes a [[Free Strike|free strike]]. Targets who haven't used a cackletongue\
      \ maneuver on this turn use it immediately at no cost. "

```
