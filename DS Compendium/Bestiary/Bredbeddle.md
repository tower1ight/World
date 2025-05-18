```ds-statblock
"name": "Bredbeddle"
"ancestry":
- "Giant"
"roles":
- "SOLO"
"level": !!int "3"
"ev": !!int "88"
"stamina": !!int "240"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "2"
"stability": !!int "4"
"free_strike": !!int "6"
"might": !!int "3"
"intuition": !!int "0"
"agility": !!int "0"
"reason": !!int "-3"
"presence": !!int "2"
"traits":
- "name": "Solo Monster"
  "effect": "- **Solo Turns**: The bredbeddle takes two turns each round. They can\
    \ use two actions on each of their turns and can take each turn after any enemy's\
    \ turn. While [[Dazed|dazed]], the bredbeddle can take one action and one maneuver per turn.\
    \ - **End Effect**: At the end of their turn, the bredbeddle can take 5 damage\
    \ to end one save ends effect affecting them. This damage can't be reduced in\
    \ any way."
- "name": "Resilient Form"
  "effect": "The bredbeddle can't be physically transformed in any way except by their\
    \ Heady or Not trait."
- "name": "Heady or Not"
  "effect": "While headless, the bredbeddle can move into a space with a severed head\
    \ and attach it to their neck. Doing so physically transforms the bredbeddle,\
    \ who takes on the size, weight, reach, and stability of the head's original owner.\
    \ These effects last until the bredbeddle is killed or beheaded, or until the\
    \ head falls off after 24 hours. A head that falls off can no longer be attached\
    \ to the bredbeddle.  A creature must succeed on a hard Might test made as a maneuver\
    \ to rip a head off the bredbeddle. If they fail, the bredbeddle can use Executioner's\
    \ Swing against them."
"abilities":
- "name": "Executioner's Swing"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Resistance"
  - "Weapon"
  "distance": "2 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "2 damage; A2 [[Bleeding|bleeding]] (save ends)"
    "t2": "4 damage; A3 [[Bleeding|bleeding]] (save ends)"
    "t3": "5 damage; A4 [[Bleeding|bleeding]] and [[Dazed|dazed]] (save ends)"
  - "name": "3 Malice"
    "effect": "The bredbeddle shifts up to 2 squares and can target additional enemies\
      \ who come within distance of this ability during the move. "
- "name": "Lop"
  "type": "Action"
  "cost": "3 Malice"
  "keywords":
  - "Attack"
  - "Magic"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "One creature"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "6 damage; [[Bleeding|bleeding]] (save ends) or M2 beheaded (see effect)"
    "t2": "10 damage; [[Bleeding|bleeding]] (save ends) or M3 beheaded (see effect)"
    "t3": "13 damage; [[Bleeding|bleeding]] (save ends) or M4 beheaded (see effect)"
  - "name": "Effect"
    "effect": "A beheaded target has their head fall into an unoccupied square adjacent\
      \ to the bredbeddle, but they remain alive. While beheaded, the target is [[Dazed|dazed]]\
      \ and can't have line of effect to any creature other than themselves. The beheaded\
      \ target can survive without their head for 24 hours, and can reattach their\
      \ head by entering its square and using a maneuver to do so. A target who remains\
      \ beheaded for 24 hours dies. "
- "name": "Scramble"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The bredbeddle must be headless to use this ability. The bredbeddle\
      \ shifts up to their speed, and can push each creature who comes within their\
      \ reach during the shift 1 square. Each square the bredbeddle leaves during\
      \ the shift becomes [[Difficult Terrain|difficult terrain]]. "
- "name": "Headway"
  "type": "Maneuver"
  "cost": "5 Malice"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 20"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage; M2 [[Dazed|dazed]] (save ends)"
    "t2": "5 damage; [[Prone|prone]]; M3 [[Dazed|dazed]] (save ends)"
    "t3": "7 damage; [[Prone|prone]]; M4 [[Dazed|dazed]] (save ends) "
  - "name": "Effect"
    "effect": "The bredbeddle must have a head in their possession (attached to them\
      \ or not), which they throw at the target. If the head was attached, the bredbeddle\
      \ becomes headless."
- "name": "Rebuke of the Fiendish Burlow"
  "type": "Triggered Action"
  "cost": "2 Malice"
  "keywords":
  - "Magic"
  "distance": "Self"
  "target": "Self"
  "trigger": "A creature targets the bredbeddle with a ranged magic attack."
  "effects":
  - "name": "Effect"
    "effect": "The bredbeddle uses the same ability against the triggering creature,\
      \ using that creature's bonus to any power rolls they make. "
- "name": "Turn Green"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "3 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "PRS RR"
    "t1": "The target turns green and is [[Slowed|slowed]] (save ends)"
    "t2": "The target turns green (save ends)"
    "t3": "No effect "
  - "name": "Effect"
    "effect": "Green shadows [[Crawl|crawl]] out from under the bredbeddle's feet and attempt\
      \ to turn each target green. The bredbeddle has a double edge on attacks made\
      \ against targets turned green in this way."
- "name": "Challenge"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Ranged 5"
  "target": "One creature who damaged the bredbeddle this encounter"
  "effects":
  - "name": "Effect"
    "effect": "The bredbeddle points at the target and issues them a challenge. If\
      \ the target refuses, they turn green (save ends). If the target accepts, the\
      \ bredbeddle shifts to a space adjacent to the target, who must make a hard\
      \ Might test with no additional modifiers."
- "name": "Headlam Rampage"
  "type": "Villain Action 3"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 2"
  "target": "Four creatures"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage; [[Bleeding|bleeding]] (save ends) or M2 beheaded (see Lop)"
    "t2": "4 damage; [[Bleeding|bleeding]] (save ends) or M3 beheaded (see Lop)"
    "t3": "5 damage; [[Bleeding|bleeding]] (save ends) or M4 beheaded (see Lop)"

```
