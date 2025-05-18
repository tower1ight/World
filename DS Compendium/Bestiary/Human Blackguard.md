```ds-statblock
"name": "[[Human]] Blackguard"
"ancestry":
- "[[Human]]"
- "Humanoid"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "38"
"stamina": !!int "80"
"immunities":
- "Magic 2"
- "Psionic 2"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "2"
"free_strike": !!int "4"
"might": !!int "3"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "2"
"presence": !!int "2"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the blackguard can take 5 damage to end one\
    \ \"save ends\" effect affecting them. This damage can't be reduced in any way."
- "name": "Heightened Supernatural Insight"
  "effect": "The blackguard can target supernatural creatures and objects within 15\
    \ squares, even if they don't have line of effect."
"abilities":
- "name": "Zweihander Swing"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "1 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "4 damage; M2 [[Slowed|slowed]] (save ends)"
    "t2": "7 damage; M3 [[Slowed|slowed]] (save ends)"
    "t3": "10 damage; M4 [[Slowed|slowed]] (save ends)"
  - "name": "Effect"
    "effect": "An ally within 10 squares of the blackguard can make a [[Free Strike|free strike]]."
  - "name": "1 Malice"
    "effect": "The ally can use their signature action instead. "
- "name": "You!"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "One enemy"
  "effects":
  - "name": "Effect"
    "effect": "The target is marked until the start of the blackguard's next turn.\
      \ The blackguard and each of their allies gain an edge and advantage on attacks\
      \ against targets marked by the blackguard. "
- "name": "Parry!"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "distance": "Melee 1"
  "target": "Self or one ally"
  "trigger": "A creature targets the blackguard or an ally adjacent to the blackguard\
    \ with an attack."
  "effects":
  - "name": "Effect"
    "effect": "The triggering attack's damage is halved. "
- "name": "[[Advance]]!"
  "type": "Villain Action 1"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The blackguard shifts up to their speed. During or after this movement,\
      \ they can use their Zweihander Swing ability twice. "
- "name": "Back!"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "5 burst"
  "target": "All enemies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Slide 5 squares. "
- "name": "I Can Throw My Blade and So Should You!"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Magic"
  - "Ranged"
  - "Weapon"
  "distance": "3 cube within 5"
  "target": "Each enemy in the cube"
  "effects":
  - "name": "Effect"
    "effect": "The blackguard uses their Zweihander Swing ability against each enemy\
      \ in the area. Each ally within 5 squares of the area can make a [[Free Strike|free strike]]\
      \ against any enemy in the area."

```
