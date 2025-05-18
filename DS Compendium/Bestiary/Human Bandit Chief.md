```ds-statblock
"name": "[[Human]] Bandit Chief"
"ancestry":
- "[[Human]]"
- "Humanoid"
"roles":
- "Leader"
"level": !!int "3"
"ev": !!int "54"
"stamina": !!int "120"
"immunities":
- "Magic 2"
- "Psionic 2"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "3"
"agility": !!int "3"
"reason": !!int "2"
"presence": !!int "2"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the bandit chief can take 5 damage to end one\
    \ \"save ends\" effect affecting them. This damage can't be reduced in any way."
- "name": "Heightened Supernatural Insight"
  "effect": "The bandit chief can target supernatural creatures and objects within\
    \ 15 squares, even if they don't have line of effect."
"abilities":
- "name": "Whip & Magic Longsword"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Melee"
  - "Weapon"
  "distance": "Melee 3"
  "target": "Two enemies or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; pull 1"
    "t2": "9 damage; pull 2"
    "t3": "12 damage; pull 3"
  - "name": "Effect"
    "effect": "A target who is adjacent to the bandit chief after the attack is resolved\
      \ takes double edge corruption damage."
  - "name": "2 Malice"
    "effect": "The bandit chief attacks an additional target. "
- "name": "Kneel, Peasant!"
  "type": "Maneuver"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One enemy or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "Push 1; M2 [[Prone|prone]]"
    "t2": "Push 2; M3 [[Prone|prone]]"
    "t3": "Push 4; M4 [[Prone|prone]]"
  - "name": "2 Malice"
    "effect": "This ability targets each enemy adjacent to the bandit chief. "
- "name": "Bloodstones"
  "type": "Triggered Action"
  "keywords":
  - "Magic"
  "distance": "Self"
  "target": "Self"
  "trigger": "The bandit chief makes a power roll."
  "effects":
  - "name": "Effect"
    "effect": "The bandit chief takes 4 corruption damage and increases the result\
      \ of the power roll by one tier. "
- "name": "Shoot!"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target makes a ranged [[Free Strike|free strike]]. "
- "name": "Form Up!"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target shifts up to their speed. Until the end of the encounter,\
      \ the bandit chief and all allies have triple edge while adjacent to a target. "
- "name": "Lead From the Front"
  "type": "Villain Action 3"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "Shift 10 squares. During or after this movement, the bandit chief can\
      \ attack up to four targets with Whip & Magic Longsword. Each ally adjacent\
      \ to a target can make a [[Free Strike|free strike]] against them."

```
