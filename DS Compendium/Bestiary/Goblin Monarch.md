```ds-statblock
"name": "Goblin [[Monarch]]"
"ancestry":
- "Goblin"
- "Humanoid"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "24"
"stamina": !!int "50"
"immunities": []
"weaknesses": []
"speed": "6 (climb)"
"size": "1S"
"stability": !!int "1"
"free_strike": !!int "3"
"might": !!int "3"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "-4"
"presence": !!int "-3"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the [[Monarch|monarch]] can take 5 damage to end one save-ends\
    \ effect affecting them. This damage can't be reduced in any way."
- "name": "Crafty"
  "effect": "The [[Monarch|monarch]] doesn't provoke opportunity attacks by moving."
"abilities":
- "name": "Handaxe"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 5"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage"
    "t2": "5 damage"
    "t3": "7 damage"
  - "name": "Effect"
    "effect": "An ally within 10 of the [[Monarch|monarch]] can make a [[Free Strike|free strike]]. "
- "name": "Get in Here!"
  "type": "Maneuver"
  "cost": "1 Malice"
  "keywords":
  - "--"
  "distance": "Ranged 20"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "Two [[Goblin Runner|goblin runners]] appear in unoccupied spaces. "
- "name": "Meat Shield"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "distance": "Melee 1"
  "target": "One ally"
  "trigger": "A creature targets the [[Monarch|monarch]] with an attack."
  "effects":
  - "name": "Effect"
    "effect": "The ally becomes the target of the triggering attack instead. "
- "name": "What Are You Waiting For?"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "Each ally"
  "effects":
  - "name": "Effect"
    "effect": "Each target can move up to their speed or make a [[Free Strike|free strike]]. "
- "name": "Focus Fire"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "One enemy"
  "effects":
  - "name": "Effect"
    "effect": "Each ally within 10 squares of the enemy can move up to their speed\
      \ toward the enemy. "
- "name": "Kill!"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target can make a [[Free Strike|free strike]] with edge."

```
