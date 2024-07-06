---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Vistana Bandit Captain"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: "Curse of Strahd p. 28"
---
# [Vistana Bandit Captain](2-Mechanics/CLI/bestiary/humanoid/vistana-bandit-captain-cos.md)
*Source: Curse of Strahd p. 28*  

```statblock
"name": "Vistana Bandit Captain (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"actions":
- "desc": "The captain makes three melee attacks: two with its scimitar and one with\
    \ its dagger. Or the captain makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "The captain adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the captain must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Vistana%20Bandit%20Captain.webp"
```
^statblock

```encounter-table
name: Vistana Bandit Captain
creatures:
 - 1: Vistana Bandit Captain
```