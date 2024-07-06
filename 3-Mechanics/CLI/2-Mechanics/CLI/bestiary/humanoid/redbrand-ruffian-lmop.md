---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/lmop
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Redbrand Ruffian"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Lost Mine of Phandelver p. 61
---
# [Redbrand Ruffian](2-Mechanics/CLI/bestiary/humanoid/redbrand-ruffian-lmop.md)
*Source: Lost Mine of Phandelver p. 61*  

Redbrand ruffians are petty thugs and ruthless enforcers skilled at intimidation and violence. They work for money and have no scruples.

```statblock
"name": "Redbrand Ruffian (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
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
- "desc": "The ruffian makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
"source":
- "LMoP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/LMoP/Redbrand%20Ruffian.webp"
```
^statblock

```encounter-table
name: Redbrand Ruffian
creatures:
 - 1: Redbrand Ruffian
```