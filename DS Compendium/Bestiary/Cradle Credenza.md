```ds-statblock
"name": "Cradle Credenza"
"ancestry":
- "Construct"
- "High Elf"
"roles":
- "Support"
"level": !!int "2"
"ev": !!int "15"
"stamina": !!int "35"
"immunities":
- "weapon 3"
"weaknesses": []
"speed": "4"
"size": "2"
"stability": !!int "3"
"free_strike": !!int "4"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "0"
"reason": !!int "0"
"presence": !!int "2"
"traits":
- "name": "[[Defend]] the Books"
  "effect": "Each ally within 5 of a creature that attacks the cradle credenza can\
    \ make a [[Free Strike|free strike]] against them."
"abilities":
- "name": "Book Wall"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The cradle credenza's speed becomes 0, and they extend themselves into\
      \ a 5-wall until the start of their next turn. Allies adjacent to the wall at\
      \ the start of their turn regain 5 Stamina and can apply the Magic keyword to\
      \ their weapon abilities until the end of their turn. "
- "name": "Elemental Chaos"
  "type": "Action"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "2 burst"
  "target": "All enemies"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 fire damage; 2 cold damage; 2 lightning damage"
    "t2": "3 fire damage; 3 cold damage; 3 lightning damage; push 3"
    "t3": "4 fire damage; 4 cold damage; 4 lightning damage; push 5 "

```
