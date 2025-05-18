```ds-statblock
"name": "High Elf Zephyr"
"ancestry":
- "Fey"
- "High Elf"
- "Humanoid"
"roles":
- "Harrier"
"level": !!int "1"
"ev": !!int "13"
"stamina": !!int "30"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "3"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Like the Wind"
  "effect": "All of the zephyr's movement is considered [[Shifting|shifting]]."
- "name": "Otherworldly Grace"
  "effect": "At the start of their turn, the zephyr can turn the duration of one save\
    \ ends effect they suffer from into EoT."
"abilities":
- "name": "Sweeping Blade"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Reach 2"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; A1 [[Prone|prone]]"
    "t2": "5 damage; A2 [[Prone|prone]]"
    "t3": "7 damage; the zephyr takes a [[Free Strike|free strike]] on a creature adjacent to the\
      \ target; A3 [[Prone|prone]]"
  - "name": "Effect"
    "effect": "Shift 2. "
- "name": "Windwalk"
  "type": "Maneuver"
  "keywords":
  - "--"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The zephyr moves up to their speed through the air. They must end this\
      \ movement on solid ground or immediately fall [[Prone|prone]]. "

```
