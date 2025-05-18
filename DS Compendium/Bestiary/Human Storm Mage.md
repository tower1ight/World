```ds-statblock
"name": "[[Human]] Storm Mage"
"ancestry":
- "[[Human]]"
- "Humanoid"
"roles":
- "Controller"
"level": !!int "3"
"ev": !!int "17"
"stamina": !!int "40"
"immunities":
- "Magic 2"
- "Psionic 2"
"weaknesses": []
"speed": "5"
"size": "1M"
"stability": !!int "0"
"free_strike": !!int "5"
"might": !!int "0"
"intuition": !!int "0"
"agility": !!int "0"
"reason": !!int "2"
"presence": !!int "1"
"traits":
- "name": "Arcane Shield"
  "effect": "The mage has triple edge against melee attacks and abilities. Whenever\
    \ the mage takes damage from an enemy adjacent to them, the enemy takes 1 lightning\
    \ damage and is pushed 2 squares."
- "name": "Studied Supernatural Insight"
  "effect": "The storm mage can target supernatural creatures and objects within 10\
    \ squares, even if they don't have line of effect."
"abilities":
- "name": "Lightning Bolt"
  "type": "Action"
  "cost": "Signature"
  "keywords":
  - "Attack"
  - "Magic"
  - "Ranged"
  "distance": "Ranged 10"
  "target": "One creature or object"
  "effects":
  - "roll": "2d10 + 2"
    "t1": "5 lightning damage"
    "t2": "8 lightning damage"
    "t3": "11 lightning damage"
  - "name": "5 Malice"
    "effect": "The ability takes the Area keyword and becomes a 10 × 1 line that targets\
      \ each creature in the area. "
- "name": "Gust of Wind"
  "type": "Maneuver"
  "cost": "3 Malice"
  "keywords":
  - "Area"
  - "Magic"
  - "Resistance"
  "distance": "5 cube within 1"
  "target": "All creatures and objects"
  "effects":
  - "roll": "MGT RR"
    "t1": "Slide 5; [[Slowed|slowed]] (save ends)"
    "t2": "Slide 3; [[Slowed|slowed]] (EoT)"
    "t3": "Slide 1"
  - "name": "Effect"
    "effect": "The gust of wind disperses gas or vapor and extinguishes any flames,\
      \ including [[Persistent|persistent]] effects. "

```
