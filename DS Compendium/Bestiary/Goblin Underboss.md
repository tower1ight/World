```ds-statblock
"name": "Goblin Underboss"
"ancestry":
- "Goblin"
- "Humanoid"
"roles":
- "Support"
"level": !!int "1"
"ev": !!int "10"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "5 (climb)"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "-1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Crafty"
  "effect": "The underboss doesn't provoke opportunity attacks by moving."
"abilities":
- "name": "Sword"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage"
    "t2": "5 damage"
    "t3": "6 damage"
  - "name": "Effect"
    "effect": "One ally adjacent to the target can make a [[Free Strike|free strike]] against them. "
- "name": "Get Reckless!"
  "type": "Maneuver"
  "keywords":
  - "Area"
  "distance": "5 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Until the start of the underboss's next turn, each target has edge\
      \ on attacks, and attacks against them have edge."
  - "name": "3 Malice"
    "effect": "Attacks don't have edge against a target. "

```
