```ds-statblock
"name": "Hag Of The Green And Rot"
"ancestry":
- "Fey"
- "Hag"
"roles":
- "Solo"
"level": !!int "3"
"ev": !!int "88"
"stamina": !!int "240"
"immunities": []
"weaknesses": []
"speed": "5 (flying, hover)"
"size": "1L"
"stability": !!int "1"
"free_strike": !!int "6"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "1"
"presence": !!int "3"
"traits":
- "name": "Solo Monster"
  "effect": "The hag takes 2 turns each round, using two actions on each turn, and\
    \ can act after an enemy's turn of their choice. While [[Dazed|dazed]], the hag can take\
    \ one action and one maneuver per turn."
- "name": "End Effect"
  "effect": "At the end of their turn, the hag can take 5 damage to end one \"save\
    \ ends\" effect affecting them. This damage can't be reduced in any way."
- "name": "Supernatural Resistance"
  "effect": "Magic and Psionic abilities used against the hag have a ban."
"abilities":
- "name": "Corrosive Claws"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1"
  "target": "Two creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "6 corruption damage; A2 [[Weakened|weakened]] (save ends)"
    "t2": "10 corruption damage; A3 [[Weakened|weakened]] (save ends)"
    "t3": "13 corruption damage; A4 [[Weakened|weakened]] (save ends)"
  - "name": "Effect"
    "effect": "A creature [[Weakened|weakened]] by this ability takes 1d6 corruption damage at\
      \ the start of each of their turns until the condition ends. "
- "name": "Soul Steal"
  "type": "Action"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "5 cube within 1"
  "target": "All enemies in the cube"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "4 corruption damage"
    "t2": "7 corruption damage; P2 target has a bane on power rolls (save ends)"
    "t3": "10 corruption damage; P3 target has a double bane on power rolls (save\
      \ ends)"
  - "name": "Effect"
    "effect": "This ability has an edge against creatures with a soul. The hag regains\
      \ Stamina equal to half the total damage dealt. "
- "name": "Shapeshifter"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  "distance": "Self"
  "target": "Self"
  "effects":
  - "name": "Effect"
    "effect": "The hag alters their body to become any Size-1 creature, such as a\
      \ house cat. If the hag uses this ability while outside of an enemy's line of\
      \ effect, the hag is considered hidden. The hag can return to their original\
      \ form as a free maneuver."
  - "name": "5 Malice"
    "effect": "The hag becomes a Size-2 creature instead, such as a bear. While in\
      \ this form, the distance of their melee abilities increases by 1 and has reach. "
- "name": "Turned Upside Down"
  "type": "Triggered Action"
  "cost": "2 Malice"
  "keywords":
  - "Area"
  - "Magic"
  "trigger": "A creature hits Shtriga Nona with a melee attack."
  "distance": "1 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "REA RR"
    "t1": "Vertical slide 5; [[Restrained|restrained]] (EoT)"
    "t2": "Slide 3; [[Slowed|slowed]] (EoT)"
    "t3": "Slide 2"
  - "name": "Effect"
    "effect": "A creature [[Restrained|restrained]] by this ability that is force moved vertically\
      \ is suspended in midair until the condition ends. "
- "name": "Snackies for Sweeties"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "5 burst"
  "target": "All creatures"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "4 poison damage; A2 [[Bleeding|bleeding]] (save ends)"
    "t2": "6 poison damage; A3 [[Bleeding|bleeding]] (save ends)"
    "t3": "4 poison damage; A4 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "The hag attaches an ornate explosive pastry to each target. Roll power\
      \ at the end of the round, targeting each creature with a pastry attached to\
      \ them and all creatures and objects within 2 of each pastry. "
  - "name": "Special"
    "effect": "An adjacent creature can attempt a hard Agility test to remove the\
      \ pastry as a maneuver. On success, the pastry is destroyed without exploding.\
      \ On failure, the hag rolls power for all pastries immediately. "
- "name": "Animal Alacrity"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "1 burst"
  "target": "All enemies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "The hag shifts up to their speed before using this action, makes a\
      \ corrosive claws attack against each target, pushes each target 2 squares,\
      \ and then shifts up to their speed again. The hag makes one power roll against\
      \ all targets. "
- "name": "Open the Oven"
  "type": "Villain Action 3"
  "keywords":
  - "Area"
  - "Melee"
  - "Weapon"
  "distance": "5 cube within 1"
  "target": "All creatures in the cube"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "6 fire damage; A2 [[Weakened|weakened]] (save ends)"
    "t2": "10 fire damage; A3 [[Weakened|weakened]] (save ends)"
    "t3": "13 fire damage; A4 [[Weakened|weakened]] (save ends)"
  - "name": "Effect"
    "effect": "The hag turns the affected area into a roiling oven. The hag gains\
      \ one edge on attacks and abilities against a creature each time they enter\
      \ an affected square or start their turn there."

```
