---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid
aliases: ["Redbrand Ruffian"]
NoteIcon: monster
BestiaryType: humanoid
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 216
---
# [Redbrand Ruffian](2-Mechanics/CLI/bestiary/humanoid/redbrand-ruffian-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 216*  

Redbrand ruffians are ruthless enforcers skilled at intimidation and violence. They work for money and have no scruples.

```statblock
"name": "Redbrand Ruffian (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Neutral Evil"
"ac": !!int "11"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "14"
- !!int "10"
- !!int "12"
- !!int "9"
- !!int "9"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
"senses": "passive Perception 9"
"languages": "Common"
"cr": "1/2"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Redbrand%20Ruffian.webp"
```
^statblock

```encounter-table
name: Redbrand Ruffian
creatures:
 - 1: Redbrand Ruffian
```