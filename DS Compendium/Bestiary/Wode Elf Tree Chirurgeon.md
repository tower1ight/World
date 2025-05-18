```ds-statblock
"name": "Wode Elf Tree Chirurgeon"
"ancestry":
- "Fey"
- "Humanoid"
- "Wode Elf"
"roles":
- "Harrier"
"level": !!int "2"
"ev": !!int "15"
"stamina": !!int "35"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "4"
"might": !!int "1"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits":
- "name": "Masking Glamor"
  "effect": "The tree chirurgeon immediately [[Hide|hides]] at the end of their turn while\
    \ in cover or concealment, even if they are observed."
"abilities":
- "name": "Wild Axe"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "[[Charge]]"
  - "Melee"
  - "Ranged"
  - "Weapon"
  "distance": "Melee 1 or Ranged 5"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 damage; push 1"
    "t2": "7 damage; push 3"
    "t3": "10 damage; push 5"
  - "name": "Effect"
    "effect": "The tree chirurgeon can make a ranged [[Free Strike|free strike]] before attacking."
  - "name": "5 Malice"
    "effect": "The tree chirurgeon uses this ability again. "
- "name": "The Wode Protects Us"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Magic"
  "distance": "Self and Ranged 5"
  "target": "Self and 3 allies"
  "effects":
  - "name": "Effect"
    "effect": "Each target [[Teleport|teleports]] to a square within 10 that has cover or concealment\
      \ from all enemies. "

```
