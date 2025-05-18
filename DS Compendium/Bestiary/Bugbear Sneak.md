```ds-statblock
"name": "Bugbear Sneak"
"ancestry":
- "Bugbear"
- "Goblin"
- "Humanoid"
"roles":
- "AMBUSHER"
"level": !!int "2"
"ev": !!int "34"
"stamina": !!int "70"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "2"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "0"
"traits": []
"abilities":
- "name": "Suckerpunch"
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
    "t1": "5 damage; A2 [[Grabbed|grabbed]]"
    "t2": "9 damage; A3 [[Grabbed|grabbed]]"
    "t3": "12 damage; [[Grabbed|grabbed]]"
  - "name": "Effect"
    "effect": "The target can't use triggered actions until the start of the next\
      \ round. This attack has double edge if the sneak started their turn hidden\
      \ from the target. "
- "name": "Dirt [[Devil]]"
  "type": "Action"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  "distance": "2 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage; I1 sneak is concealed from the target (save ends)"
    "t2": "3 damage; I2 sneak is concealed from the target (save ends)"
    "t3": "4 damage; I3 sneak is concealed from the target (save ends)"
  - "name": "Effect"
    "effect": "The sneak shifts up to their speed and [[Hide|hides]] after using this ability. "
- "name": "Carving Dagger"
  "type": "Action"
  "keywords":
  - "Attack"
  - "Ranged"
  - "Weapon"
  "distance": "Ranged 8"
  "target": "2 creatures or objects"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; M1 [[Bleeding|bleeding]] (save ends)"
    "t2": "9 damage; M2 [[Bleeding|bleeding]] (save ends)"
    "t3": "12 damage; M3 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "Targets can't [[Hide|hide]] from the sneak or their allies while [[Bleeding|bleeding]] from\
      \ this ability. "
- "name": "Throw"
  "type": "Maneuver"
  "keywords":
  - "Attack"
  - "Melee"
  "distance": "Melee 1"
  "target": "1 creature or object [[Grabbed|grabbed]] by the sneak"
  "effects":
  - "name": "Effect"
    "effect": "Vertical push 4. Ally targets don't take damage from being force moved. "
- "name": "Catcher"
  "type": "Free Triggered Action"
  "keywords":
  - "--"
  "distance": "Melee 1"
  "target": "1 size 1 creature or object"
  "trigger": "The target is force moved into a square adjacent to the sneak."
  "effects":
  - "name": "Effect"
    "effect": "The target is [[Grabbed|grabbed]] by the sneak. "
- "name": "Misdirection"
  "type": "Triggered Action"
  "cost": "1 Malice"
  "keywords":
  - "--"
  "distance": "Special"
  "target": "1 enemy"
  "trigger": "A target attacks the sneak."
  "effects":
  - "name": "Effect"
    "effect": "The sneak chooses an enemy within distance of the attack. The attack\
      \ targets that enemy instead."

```
