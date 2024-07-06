---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Reduced-Threat Behir"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: "Tales from the Yawning Portal p. 113"
---
# [Reduced-Threat Behir](2-Mechanics/CLI/bestiary/monstrosity/reduced-threat-behir-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Behir (TftYP)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "23"
- !!int "16"
- !!int "18"
- !!int "7"
- !!int "14"
- !!int "12"
"speed": "50 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"damage_immunities": "lightning"
"senses": "darkvision 90 ft., passive Perception 16"
"languages": "Draconic"
"cr": "11"
"actions":
- "desc": "The behir makes two attacks: one with its bite and one to constrict."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d10 + 6) piercing damage."
  "name": "Bite"
- "desc": "The behir exhales a line of lightning that is 20 feet long and 5 feet wide.\
    \ Each creature in that line must make a DC 16 Dexterity saving throw, taking\
    \ 66 (12d10) lightning damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Lightning Breath (Recharge 5-6)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Behir.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Behir
creatures:
 - 1: Reduced-Threat Behir
```