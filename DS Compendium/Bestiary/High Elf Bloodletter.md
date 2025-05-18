```ds-statblock
"name": "High Elf Bloodletter"
"ancestry":
- "Fey"
- "High Elf"
- "Humanoid"
"roles":
- "Ambusher"
"level": !!int "1"
"ev": !!int "7"
"stamina": !!int "10"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "1"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits":
- "name": "Otherworldly Grace"
  "effect": "At the start of their turn, the scribe can turn the duration of one save\
    \ ends effect they suffer from into EoT."
"abilities":
- "name": "Razor's Edge"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "4 damage; R1 [[Bleeding|bleeding]] (save ends)"
    "t2": "7 damage; R2 [[Bleeding|bleeding]] (save ends)"
    "t3": "10 damage; R3 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "A creature [[Bleeding|bleeding]] from this ability takes edge from attacks. "
- "name": "Blood Haze"
  "type": "Maneuver"
  "cost": "2 Malice"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "3 burst"
  "target": "Special"
  "effects":
  - "name": "Effect"
    "effect": "The bloodletter creates a cloud of blood vapor in the area until the\
      \ end of the next round. The cloud blocks line of effect for enemies, and an\
      \ enemy has Magic weakness 3 occupying an affected square. The bloodletter then\
      \ shifts up to their speed, hiding if they end their movement under concealment. "

```
