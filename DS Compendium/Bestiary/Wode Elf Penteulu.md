```ds-statblock
"name": "Wode Elf Penteulu"
"ancestry":
- "Fey"
- "Humanoid"
- "Wode Elf"
"roles":
- "Leader"
"level": !!int "3"
"ev": !!int "60"
"stamina": !!int "120"
"immunities": []
"weaknesses": []
"speed": "7 ([[Teleport|teleport]])"
"size": "1M"
"stability": !!int "2"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "2"
"agility": !!int "3"
"reason": !!int "2"
"presence": !!int "2"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the penteulu can take 5 damage to end one save\
    \ ends effect affecting them. This damage can't be reduced in any way."
- "name": "[[Hunter]]'s Glamor"
  "effect": "The penteulu immediately [[Hide|hides]] at the end of their turn, even if they\
    \ are observed."
"abilities":
- "name": "Wodeblade"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "3 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; M2 [[Restrained|restrained]] (save ends)"
    "t2": "9 damage; M3 [[Restrained|restrained]] (save ends)"
    "t3": "12 damage; M4 [[Restrained|restrained]] (save ends)"
  - "name": "Effect"
    "effect": "The penteulu deals damage to each target one at a time and can [[Teleport|teleport]]\
      \ 3 squares after damaging a target."
  - "name": "3 Malice"
    "effect": "Targets [[Restrained|restrained]] by this ability take an additional **+1**. "
- "name": "Fairness is a [[Human]] Concept"
  "type": "Maneuver"
  "cost": "5 Malice"
  "keywords":
  - "Area"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target can make a [[Free Strike|free strike]] and then shifts 3. A target immediately\
      \ [[Hide|hides]] at the end of the penteulu's turn while in cover or concealment. "
- "name": "Wode Sickness"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "trigger": "An ally ends their turn."
  "distance": "Ranged 10"
  "target": "1 enemy"
  "effects":
  - "name": "Effect"
    "effect": "The target must take their turn now, if they have not already taken\
      \ it. **P3** The target is [[Bleeding|bleeding]] and has a bane on their attacks until the\
      \ end of their turn. "
- "name": "You Will ALL Witness my Blade"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  "distance": "5 burst"
  "target": "All enemies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "The penteulu makes a Wodeblade attack against each target with **+1**. "
- "name": "Suppressing Volley"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  "distance": "5 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "The penteulu makes a Wodeblade attack against a single creature or\
      \ object. Each target then makes a [[Free Strike|free strike]]. "
- "name": "Is it Now or is it Then? Where are We?"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  "distance": "Self and 5 burst"
  "target": "Self and all allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target becomes invisible until the start of the next round. The\
      \ penteulu then makes a Wodeblade attack."

```
