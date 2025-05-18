```ds-statblock
"name": "Wode Elf Green Seer"
"ancestry":
- "Fey"
- "Humanoid"
- "Wode Elf"
"roles":
- "Hexer"
"level": !!int "1"
"ev": !!int "11"
"stamina": !!int "20"
"immunities": []
"weaknesses": []
"speed": "7"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "3"
"might": !!int "0"
"intuition": !!int "2"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "1"
"traits":
- "name": "Masking Glamor"
  "effect": "The green seer immediately [[Hide|hides]] at the end of their turn while in cover\
    \ or concealment, even if they are observed."
"abilities":
- "name": "The Forest's Embrace"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "1 creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "3 damage; I1 [[Restrained|restrained]] (save ends)"
    "t2": "5 damage; I2 [[Restrained|restrained]] (save ends)"
    "t3": "7 damage; I3 [[Restrained|restrained]] (save ends)"
  - "name": "Effect"
    "effect": "A creature [[Restrained|restrained]] by this ability can't [[Search For Hidden Creatures|search for hidden creatures]]\
      \ until the condition ends. "
- "name": "The Natural Cycle"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Magic"
  - "Ranged"
  - "Resistance"
  "distance": "Ranged 10"
  "target": "2 creatures"
  "effects":
  - "roll": "PRS RR"
    "t1": "Target is [[Bleeding|bleeding]] and has a bane on their attacks (save ends)"
    "t2": "Target has a bane on their attacks (save ends)"
    "t3": "No effect "
- "name": "Foreseen Punishment"
  "type": "Free Triggered Action"
  "keywords":
  - "--"
  "distance": "Ranged 5"
  "target": "1 creature"
  "trigger": "The triggering creature uses a triggered action targeting the green\
    \ seer or an ally within distance."
  "effects":
  - "name": "Effect"
    "effect": "The green seer makes a [[Free Strike|free strike]] against the target. "

```
