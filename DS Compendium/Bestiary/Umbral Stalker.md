```ds-statblock
"name": "Umbral Stalker"
"ancestry":
- "Incorporeal"
- "Undead"
"roles":
- "Ambusher"
"level": !!int "1"
"ev": !!int "9"
"stamina": !!int "15"
"immunities":
- "Corruption 3"
- "Poison 3"
"weaknesses": []
"speed": "7 (climb)"
"size": "1M"
"stability": !!int "1"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Corruptive Phasing"
  "effect": "The umbral stalker can move through other creatures and objects at normal\
    \ speed. The first time in a round that the umbral stalker passes through a creature,\
    \ that creature takes 2 corruption damage."
"abilities":
- "name": "Chilling Grasp"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Melee"
  "distance": "Melee 1"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 cold damage"
    "t2": "5 cold damage"
    "t3": "6 cold damage"
  - "name": "Effect"
    "effect": "The shadow can shift up to 2 squares before or after this attack. "
- "name": "Freezing Dark"
  "type": "Action"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Magic"
  - "Ranged"
  "distance": "3 cube within 1"
  "target": "Each enemy in the cube"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "1 cold damage"
    "t2": "2 cold damage"
    "t3": "3 cold damage"
  - "name": "Effect"
    "effect": "Until the end of the umbral stalker's next turn, the area is concealed\
      \ and blocks line of effect for all enemies. "
- "name": "Shadow [[Jump]]"
  "type": "Free Maneuver"
  "cost": "1 Malice"
  "effects":
  - "name": "Effect"
    "effect": "The umbral stalker [[Teleport|teleports]] to an unoccupied space in concealment\
      \ within 10 squares. "

```
