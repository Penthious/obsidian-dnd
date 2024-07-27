---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/any-race
- npc
aliases: ["White Jade Emperor"]
NoteIcon: npc
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: "Journeys through the Radiant Citadel p. 197"
---
# [White Jade Emperor](2-Mechanics/CLI/bestiary/npc/white-jade-emperor-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 197*  

```statblock
"name": "White Jade Emperor (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any two languages, Dwarvish"
"cr": "1/8"
"traits":
- "desc": "White"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "The emperor adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the emperor must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/White%20Jade%20Emperor.webp"
```
^statblock

```encounter-table
name: White Jade Emperor
creatures:
 - 1: White Jade Emperor
```