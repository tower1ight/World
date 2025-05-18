```ds-statblock
"name": "Bugbear Channeler"
"ancestry":
- "Bugbear"
- "Goblin"
- "Humanoid"
"roles":
- "CONTROLLER"
"level": !!int "2"
"ev": !!int "30"
"stamina": !!int "60"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "1"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "2"
"presence": !!int "2"
"traits": []
"abilities":
- "name": "Shape Earth"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 8"
  "target": "2 creatures or objects on the ground"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; pull 2"
    "t2": "8 damage; pull 3"
    "t3": "11 damage; pull 4"
  - "name": "Effect"
    "effect": "Each square that a target is pulled through becomes [[Difficult Terrain|difficult terrain]]. "
- "name": "Blistering Element"
  "type": "Action"
  "keywords":
  - "Area"
  - "Magic"
  "distance": "3 burst"
  "target": "All enemies in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 damage; M1 [[Bleeding|bleeding]] (save ends)"
    "t2": "3 damage; M2 [[Bleeding|bleeding]] (save ends)"
    "t3": "4 damage; M3 [[Bleeding|bleeding]] (save ends)"
  - "name": "Effect"
    "effect": "The channeler chooses one of the following damage types for the damage:\
      \ cold, fire, corruption, lightning, or poison. "
- "name": "Green Reshape"
  "type": "Action"
  "cost": "5 Malice"
  "keywords":
  - "Magic"
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 5"
  "target": "1 creature"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 damage; P1 [[Slowed|slowed]] (save ends)"
    "t2": "8 damage; P2 shapechanged (save ends)"
    "t3": "11 damage; P3 shapechanged (save ends)"
  - "name": "Effect"
    "effect": "A shapechanged creature becomes plant-like with bark skin and leafy\
      \ hair. They are [[Slowed|slowed]] and have fire weakness 10 while they have this effect. "
- "name": "Throw"
  "type": "Maneuver"
  "keywords":
  - "Attack"
  - "Melee"
  "distance": "Melee 1"
  "target": "1 creature or object [[Grabbed|grabbed]] by the channeler"
  "effects":
  - "name": "Effect"
    "effect": "Vertical push 3; ally targets don't take damage from being force moved. "
- "name": "Catcher"
  "type": "Free Triggered Action"
  "keywords":
  - "--"
  "distance": "Melee 1"
  "target": "1 size 1 creature or object"
  "trigger": "The target is force moved into a square adjacent to the channeler."
  "effects":
  - "name": "Effect"
    "effect": "The target is [[Grabbed|grabbed]] by the channeler. "
- "name": "Brambleguard"
  "type": "Triggered Action"
  "cost": "1 Malice"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 5"
  "target": "1 ally"
  "trigger": "The target takes non-fire damage."
  "effects":
  - "name": "Effect"
    "effect": "The channeler covers the target in thorns and halves the damage. If\
      \ the damage was caused by a melee attack, the attacker takes 5 damage."

```
