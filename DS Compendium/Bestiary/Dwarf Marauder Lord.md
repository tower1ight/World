```ds-statblock
"name": "[[Dwarf]] Marauder Lord"
"ancestry":
- "[[Dwarf]]"
- "Humanoid"
"roles":
- "Leader"
"level": !!int "3"
"ev": !!int "60"
"stamina": !!int "130"
"immunities": []
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "4"
"free_strike": !!int "5"
"might": !!int "3"
"intuition": !!int "1"
"agility": !!int "0"
"reason": !!int "2"
"presence": !!int "0"
"traits":
- "name": "End Effect"
  "effect": "At the end of their turn, the marauder lord can take 5 damage to end\
    \ one save-ends effect affecting them. This damage can't be reduced in any way."
"abilities":
- "name": "Levitating Axes"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Melee"
  - "Weapon"
  "distance": "Melee 1 or Ranged 10"
  "target": "3 creatures or objects"
  "effects":
  - "roll": "2d10 + 3"
    "t1": "5 damage; slide 1"
    "t2": "9 damage; slide 3"
    "t3": "12 damage; slide 5"
  - "name": "Effect"
    "effect": "A target [[Restrained|restrained]] by a [[Dwarf|dwarf]] can be slid by this attack."
  - "name": "3 Malice"
    "effect": "A target that is force moved adjacent to an ally with this ability\
      \ is [[Restrained|restrained]] (EoT). "
- "name": "Magnetomancy"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "1 creature or object"
  "effects":
  - "name": "Effect"
    "effect": "Vertical slide 5. A target [[Restrained|restrained]] by a [[Dwarf|dwarf]] can be slid by this\
      \ ability."
  - "name": "5 Malice"
    "effect": "This ability gains the Area keyword, its distance becomes 10 burst,\
      \ and it now targets [[Restrained|restrained]] creatures. "
- "name": "Your Weapon is Useless"
  "type": "Triggered Action"
  "keywords":
  - "Magic"
  "distance": "Self or Ranged 10"
  "target": "Self or 1 ally"
  "trigger": "A creature makes a weapon attack against the target."
  "effects":
  - "name": "Effect"
    "effect": "The target takes half damage from the attack. The attacker takes 5\
      \ damage. "
- "name": "Ajax Will Pay Well for These Specimens"
  "type": "Villain Action 1"
  "keywords":
  - "Area"
  - "Weapon"
  "distance": "5 cube within 10"
  "target": "All enemies in the cube"
  "effects":
  - "name": "Effect"
    "effect": "The marauder lord uses Levitating Axes against each target. The marauder\
      \ lord makes one power roll against all targets. "
- "name": "Don't Let Them Escape!"
  "type": "Villain Action 2"
  "keywords":
  - "Area"
  "distance": "5 burst"
  "target": "All allies in the burst"
  "effects":
  - "name": "Effect"
    "effect": "Each target shifts up to their speed. The marauder lord then uses Levitating\
      \ Axes. "
- "name": "Test Your Metal!"
  "type": "Villain Action 3"
  "keywords":
  - "--"
  "distance": "Ranged 10"
  "target": "special"
  "effects":
  - "name": "Effect"
    "effect": "The marauder lord creates three 2-square metal objects in unoccupied\
      \ squares within distance. When the marauder lord uses Magnetomancy, they can\
      \ additionally target one of these objects."

```
