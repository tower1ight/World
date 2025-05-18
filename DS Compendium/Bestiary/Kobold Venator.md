```ds-statblock
"name": "Kobold Venator"
"ancestry":
- "Humanoid"
- "Kobold"
"roles":
- "Ambusher"
"level": !!int "1"
"ev": !!int "9"
"stamina": !!int "15"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1S"
"stability": !!int "0"
"free_strike": !!int "1"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "2"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Lost in the Crowd"
  "effect": "If the venator is adjacent to an ally, they can use the [[Hide|hide]] maneuver,\
    \ even if observed."
- "name": "Not What I Seem"
  "effect": "The venator begins the encounter disguised as a minion from their squad.\
    \ The venator has a double edge on their first attack of the encounter when they\
    \ reveal themselves."
- "name": "Shield? Shield!"
  "effect": "The venator has increased Stability by 1 and can act as cover for allies\
    \ when adjacent to an ally who also has this trait."
"abilities":
- "name": "Dolobra & Net"
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
    "t1": "2 damage; 1 [[Restrained|restrained]] (save ends)"
    "t2": "5 damage; 2 [[Restrained|restrained]] (save ends)"
    "t3": "6 damage; 3 [[Restrained|restrained]] (save ends)"
  - "name": "3 Malice"
    "effect": "Creatures and objects [[Restrained|restrained]] by this ability take 2 fire damage\
      \ at the start of each of their turns. "

```
