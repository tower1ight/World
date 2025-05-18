```ds-statblock
"name": "Radenwight [[Maestro]]"
"ancestry":
- "Humanoid"
- "Radenwight"
"roles":
- "Leader"
"level": !!int "1"
"ev": !!int "38"
"stamina": !!int "80"
"immunities": []
"weaknesses": []
"speed": "5 (climb)"
"size": "1S"
"stability": !!int "1"
"free_strike": !!int "5"
"might": !!int "-2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "3"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the [[Maestro|maestro]] can take 5 damage to end one save\
    \ ends effect affecting them. This damage can't be reduced in any way."
"abilities":
- "name": "Cacophony"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "5 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 sonic damage; slide 1; the [[Maestro|maestro]] can shift 1 square"
    "t2": "5 sonic damage; slide 3; the [[Maestro|maestro]] can shift 3 squares"
    "t3": "7 sonic damage; slide 5; the [[Maestro|maestro]] can shift 5 squares"
  - "name": "Effect"
    "effect": "Each ally within distance can use Ready Rodent as a free triggered\
      \ action once before the end of the round. "
- "name": "Tempo Change"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 10"
  "target": "Two enemies"
  "effects":
  - "roll": "PRS RR"
    "t1": "[[Slowed]] (save ends)"
    "t2": "[[Slowed]] (EoT)"
    "t3": "No effect"
  - "name": "3 Malice"
    "effect": "Each ally within 3 of a target has their speed increased by 2 until\
      \ the end of their next turn. "
- "name": "Ever Ready Rodent"
  "type": "Free Triggered Action"
  "cost": "2 Malice"
  "keywords":
  - "Magic"
  - "Melee"
  - "Ranged"
  "distance": "Ranged 5"
  "target": "One creature"
  "trigger": "The target deals damage to an ally or takes damage from an ally."
  "effects":
  - "name": "Effect"
    "effect": "The [[Maestro|maestro]] makes a [[Free Strike|free strike]] against the target. The [[Maestro|maestro]] can\
      \ only use this ability once per turn. "
- "name": "Overture"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target shifts up to their speed or takes the [[Defend]] action. "
- "name": "Solo Act"
  "type": "Villain Action 2"
  "keywords":
  - "Ranged"
  "distance": "Ranged 15"
  "target": "One creature"
  "effects":
  - "name": "Effect"
    "effect": "Until the end of their next turn, the target gains invisibility, a\
      \ boon, and their speed is doubled. "
- "name": "Rondo of Rat"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All dead allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target stands, makes a [[Free Strike|free strike]], then collapses again. Allies\
      \ of the targets can use Ready Rodent as a free triggered action once in conjunction\
      \ with these [[Free Strike|free strikes]]."

```
