```ds-statblock
"name": "Last Laugh"
"ancestry":
- "Fiend"
- "Gnoll"
"roles":
- "Leader"
"level": !!int "2"
"ev": !!int "30"
"stamina": !!int "70"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "4"
"might": !!int "3"
"intuition": !!int "0"
"agility": !!int "3"
"reason": !!int "0"
"presence": !!int "3"
"traits":
- "name": "Death Rampage"
  "effect": "Whenever an ally within 5 is reduced to 0 Stamina, the last laugh moves\
    \ up to their speed and either chooses to target 2 creatures with [[Free Strike|free strikes]]\
    \ or one creature with shrapnel whip."
- "name": "Running Joke"
  "effect": "If the last laugh is reduced to 0 Stamina while there are still gnolls\
    \ on the battle map, one gnoll on the map is transformed into the last laugh,\
    \ keeping the gnoll's Stamina."
"abilities":
- "name": "Shrapnel Whip"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Reach 2"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "4 damage; A2 [[Bleeding|bleeding]] (save ends)"
    "t2": "7 damage; A3 [[Bleeding|bleeding]] (save ends)"
    "t3": "10 damage; A4 [[Bleeding|bleeding]] and [[Dazed|dazed]] (save ends)"
  - "name": "Effect"
    "effect": "An ally targeted by this ability makes a [[Free Strike|free strike]] instead of taking\
      \ damage. "
- "name": "Cackletongue"
  "type": "Maneuver"
  "cost": "4 Malice"
  "keywords":
  - "--"
  "distance": "Self and 5 burst"
  "target": "Self and all allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target has edge until the start of the last laugh's next turn.\
      \ Targets who haven't used a cackletongue maneuver on this turn use it immediately\
      \ at no cost. "
- "name": "Not the Best Time to Laugh"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "5 burst"
  "target": "All enemies"
  "effects":
  - "roll": "INU RR"
    "t1": "[[Frightened]] of the last laugh (save ends)"
    "t2": "[[Frightened]] of the last laugh (EoT)"
    "t3": "No effect"
  - "name": "Effect"
    "effect": "While [[Frightened|frightened]] by this ability, targets laugh uncontrollably and\
      \ cannot use triggered actions. "
- "name": "Call Up From The Abyss"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "The last laugh summons 5 [[Gnoll Wildling|gnoll wildlings]] and 5 [[Abyssal Hyena|abyssal hyenas]] into\
      \ unoccupied spaces. "
- "name": "Edacity"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  "distance": "Self and 10 burst"
  "target": "Self and all allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target moves up to their speed and makes a [[Free Strike|free strike]]. Creatures\
      \ that take damage from this villain action are also knocked [[Prone|prone]]."

```
