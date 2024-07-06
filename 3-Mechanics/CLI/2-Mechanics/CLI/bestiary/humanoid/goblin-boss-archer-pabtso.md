---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1
- monster/size/small
- monster/type/humanoid/goblinoid
aliases: ["Goblin Boss Archer"]
NoteIcon: monster
BestiaryType: humanoid (goblinoid)
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 60
---
# [Goblin Boss Archer](2-Mechanics/CLI/bestiary/humanoid/goblin-boss-archer-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 60*  

```statblock
"name": "Goblin Boss Archer (PaBTSO)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"traits":
- "desc": "The goblin can take the Disengage or Hide action as a bonus action on each\
    \ of its turns."
  "name": "Nimble Escape"
"actions":
- "desc": "The goblin makes two attacks with its scimitar. The second attack has disadvantage."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80 ft./320 ft., one target.\
    \ Hit: 5 (1d6 + 2) piercing damage."
  "name": "Shortbow"
"reactions":
- "desc": "When a creature the goblin can see targets it with an attack, the goblin\
    \ chooses another goblin within 5 feet of it. The two goblins swap places, and\
    \ the chosen goblin becomes the target instead."
  "name": "Redirect Attack"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Goblin%20Boss%20Archer.webp"
```
^statblock

```encounter-table
name: Goblin Boss Archer
creatures:
 - 1: Goblin Boss Archer
```