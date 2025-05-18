```ds-statblock
"name": "War Dog Cognivite"
"ancestry":
- "Humanoid"
- "War Dog"
"roles":
- "Defender"
"level": !!int "1"
"ev": !!int "11"
"stamina": !!int "25"
"immunities":
- "Psychic 3"
"weaknesses": []
"speed": "5 ([[Fly|fly]])"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "2"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "1"
"reason": !!int "0"
"presence": !!int "2"
"traits":
- "name": "Loyalty Collar"
  "effect": "When the cognivite dies, they explode, dealing 1d6 damage to each adjacent\
    \ enemy."
"abilities":
- "name": "Synlirii Grafts"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Area"
  - "Psionic"
  "distance": "1 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "2 psychic damage; vertical slide 1"
    "t2": "4 psychic damage; vertical slide 2"
    "t3": "5 psychic damage; vertical slide 3 "
- "name": "Posthumous Promotion"
  "type": "Maneuver"
  "keywords":
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "One war dog with a loyalty collar"
  "effects":
  - "name": "Effect"
    "effect": "The target's loyalty collar detonates, killing them instantly. "
- "name": "The Voice"
  "type": "Maneuver"
  "cost": "1 Malice"
  "keywords":
  - "Area"
  - "Psionic"
  "distance": "5 burst"
  "target": "Each enemy in the burst"
  "effects":
  - "name": "Effect"
    "effect": "The cognivite chooses an ally within 10 squares, then chooses whether\
      \ each target is [[Taunted|taunted]] by the ally or the ally has **cover** whenever they're\
      \ attacked by a target until the start of the cognivite's next turn. "

```
