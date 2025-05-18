```ds-statblock
"name": "Gnoll Abyssal Archer"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Artillery"
"level": !!int "2"
"ev": !!int "12"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "4"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "1"
"presence": !!int "-1"
"traits":
- "name": "Death Frenzy"
  "effect": "Whenever an ally within 5 is reduced to 0 Stamina, the abyssal archer\
    \ moves up to their speed and makes a [[Free Strike|free strike]]."
- "name": "Bloodscent"
  "effect": "The abyssal archer can target creatures not at full Stamina with abilities,\
    \ even if they don't have line of effect."
"abilities":
- "name": "Dark Longbow"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 10"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 corruption damage; M1 [[Slowed|slowed]] (save ends)"
    "t2": "7 corruption damage; M2 [[Slowed|slowed]] (save ends)"
    "t3": "10 corruption damage; M3 [[Slowed|slowed]] (save ends)"
  - "name": "Effect"
    "effect": "This attack has edge against creatures the abyssal archer has previously\
      \ targeted. "
- "name": "Cackletongue"
  "type": "Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "--"
  "distance": "Self and 2 burst"
  "target": "Self and all allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target has an edge on their next attack before the end of their\
      \ next turn. Targets who haven't used a cackletongue maneuver on this turn use\
      \ it immediately at no cost. "

```
