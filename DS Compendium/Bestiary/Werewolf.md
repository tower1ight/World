```ds-statblock
"name": "Werewolf"
"ancestry":
- "Beast"
- "Humanoid"
"roles":
- "Solo"
"level": !!int "1"
"ev": !!int "60"
"stamina": !!int "120"
"immunities":
- "weapon 5"
"weaknesses": []
"speed": "8"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "3"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "-1"
"presence": !!int "1"
"traits":
- "name": "Solo Monster"
  "effect": "- **Solo Turns**: The werewolf takes 2 turns each round. They can use\
    \ two actions on each of their turns and can take each turn after an enemy turn\
    \ they choose. While [[Dazed|dazed]], the werewolf can take one action and one maneuver\
    \ per turn. - **End Effect**: The werewolf takes 5 damage and ends one EoE effect\
    \ affecting them at the end of their turn."
- "name": "Shapeshifter"
  "effect": "The werewolf enters combat in their hybrid humanoid form. Their shape\
    \ can't change via any effects beyond their own ability."
- "name": "Ferocity"
  "effect": "The werewolf's abilities are capable of inflicting ferocity points on\
    \ non-stormwight enemies. If a creature has 10 or more ferocity at the start of\
    \ their turn, they spend all their ferocity and either make a [[Free Strike|free strike]] at the\
    \ nearest creature or shift up to their speed towards the nearest creature and\
    \ take a [[Free Strike|free strike]]. Non-stormwight creatures that take damage in this way gain\
    \ 1 ferocity. All accumulated ferocity disappears after completing a respite."
- "name": "Vukenstep"
  "effect": "The werewolf ignores [[Difficult Terrain|difficult terrain]]."
"abilities":
- "name": "Accursed Bite"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "7 damage; 2 ferocity"
    "t2": "10 damage; 4 ferocity"
    "t3": "13 damage; 5 ferocity"
  - "name": "2 Malice"
    "effect": "The target has P0 lycanthropy. The potency of this attack increases\
      \ by 1 each time the werewolf forces the same target to resist it."
  - "name": "Effect"
    "effect": "A creature afflicted with lycanthropy accumulates 2 ferocity at the\
      \ end of each of their turns whenever they're in combat. Their ferocity does\
      \ not disappear after completing a respite; they must complete the Find a Cure\
      \ project to end this condition. "
- "name": "Claws"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "4 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage"
    "t2": "4 damage; 1 ferocity; M2 push 3"
    "t3": "5 damage; 3 ferocity; M3 vertical slide 3 "
- "name": "Berserker Slash"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The werewolf shifts up to their speed and makes a claw attack against\
      \ each creature who comes within 1 of the werewolf during the move. The werewolf\
      \ makes one power roll against all targets. "
- "name": "Wall Leap"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The werewolf leaps 4 squares. If they end this movement at a wall,\
      \ the werewolf leaps off the wall 4 squares and makes a melee [[Free Strike|free strike]]. "
- "name": "Facepalm and Head Slam"
  "type": "Triggered Action"
  "cost": "2 Malice"
  "keywords":
  - "--"
  "trigger": "The target declares a melee attack against the werewolf after charging\
    \ or moving 3 or more squares in a straight line towards them."
  "distance": "Melee 1"
  "target": "1 creature"
  "effects":
  - "name": "Effect"
    "effect": "Target is knocked [[Prone|prone]] and takes 5 damage before the attack begins. "
- "name": "Howl"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Resistance"
  "distance": "5 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "INU RR"
    "t1": "Target moves up to their speed away from the werewolf; [[Frightened|frightened]] (save\
      \ ends)"
    "t2": "[[Frightened]] (EoT)"
    "t3": "no effect"
  - "name": "Effect"
    "effect": "Enemies that have 1 or more ferocity gain 4 ferocity and howl along\
      \ with the werewolf. "
- "name": "Full Wolf"
  "type": "Villain Action 2"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The werewolf changes into a massive wolf, pushing adjacent creatures\
      \ out of their way and moving into a square that can accommodate their new size.\
      \ Until they die or the end of the encounter, their Speed is 10, their Size\
      \ is 3, and their Stability is 2. Each of the werewolf's attacks has **edge**\
      \ and inflicts an additional 1 ferocity. The potency of the werewolf's Accursed\
      \ Bite increases by 1. "
- "name": "Rampage"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "2 burst"
  "target": "All creatures in the burst"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "3 damage; 2 ferocity"
    "t2": "4 damage; 4 ferocity"
    "t3": "5 damage; 8 ferocity; [[Prone|prone]]"
  - "name": "Effect"
    "effect": "The werewolf shifts up to twice their speed either before or after\
      \ the attack."

```
