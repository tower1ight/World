```ds-statblock
"name": "High Elf Ordinator"
"ancestry":
- "Fey"
- "High Elf"
- "Humanoid"
"roles":
- "Leader"
"level": !!int "3"
"ev": !!int "60"
"stamina": !!int "120"
"immunities": []
"weaknesses": []
"speed": "5 ([[Fly|fly]])"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "0"
"intuition": !!int "2"
"agility": !!int "2"
"reason": !!int "3"
"presence": !!int "3"
"traits":
- "name": "Otherworldly Grace"
  "effect": "At the start of their turn, the ordinator can turn the duration of one\
    \ save ends effect they suffer from into EoT."
"abilities":
- "name": "Lightning Rod"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 20"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 lightning damage; R2 [[Dazed|dazed]] (save ends)"
    "t2": "8 lightning damage; R3 [[Dazed|dazed]] (save ends)"
    "t3": "12 lightning damage; R4 [[Dazed|dazed]] (save ends)"
  - "name": "Effect"
    "effect": "High elves have edge on attacks and abilities against the target until\
      \ the start of the ordinator's next turn. "
- "name": "Call Forth Elementals"
  "type": "Maneuver"
  "cost": "2+ Malice"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "The ordinator summons 1 [[Elemental Mote|elemental mote]] for every 2 malice spent into\
      \ unoccupied squares within distance. "
- "name": "Conjure Cradle"
  "type": "Free Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "The ordinator conjures 3 dead [[Cradle Crow|cradle crows]], 1 dead [[Cradle Horse|cradle horse]], or\
      \ 1 dead [[Cradle Credenza|cradle credenza]] into unoccupied squares within distance. "
- "name": "Enough!"
  "type": "Triggered Action"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "1 enemy"
  "trigger": "The target makes an attack against the ordinator or an ally within distance."
  "effects":
  - "name": "Effect"
    "effect": "The ordinator uses the Lightning Rod ability against the target. "
- "name": "Fountains Roar, Now Free From The Earth"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target glows, ending one condition on themselves and then moving\
      \ up to twice their speed. "
- "name": "And The Sun Forsook Her Children"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "5 cube within 10"
  "target": "All enemies in the cube"
  "effects":
  - "roll": "PRS RR"
    "t1": "8 corruption damage; pull 5 towards center of cube"
    "t2": "5 corruption damage; pull 3 towards center of cube"
    "t3": "Pull 1 towards center of cube"
  - "name": "Effect"
    "effect": "The affected area becomes darkened, and its space warps violently in\
      \ every direction. "
- "name": "But We Will Change Her Mind."
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "10 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target radiates wisps of magic and makes a [[Free Strike|free strike]] that has\
      \ the Magic keyword. "

```
