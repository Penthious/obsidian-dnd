---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dip
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/half-orc
- monster/type/humanoid/shapechanger
aliases: ["Anchorite of Talos"]
NoteIcon: monster
BestiaryType: humanoid (half-orc, shapechanger)
SourceType: Bestiary
BookSource: "Dragon of Icespire Peak p. 51"
---
# [Anchorite of Talos](2-Mechanics/CLI/bestiary/humanoid/anchorite-of-talos-dip.md)
*Source: Dragon of Icespire Peak p. 51*  

These religious recluses are granted spellcasting power by Talos, the god of storms. Their human ancestors bred with orcs, and now all anchorites of Talos are half-orcs.

```statblock
"name": "Anchorite of Talos (DIP)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-orc, shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "9"
- !!int "15"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "1"
  "Stealth": !!int "3"
  "Survival": !!int "4"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Orc"
"cr": "3"
"traits":
- "desc": "The anchorite's innate spellcasting ability is Wisdom (spell save DC 12).\
    \ It can innately cast the following spells, requiring no material components:\n\
    \n1/day each: [augury](/2-Mechanics/CLI/spells/augury.md), [bless](/2-Mechanics/CLI/spells/bless.md),\
    \ [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md) (8d6 damage),\
    \ [revivify](/2-Mechanics/CLI/spells/revivify.md)\n\n3/day: [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\
    \ (2d8 damage)"
  "name": "Innate Spellcasting"
- "desc": "The anchorite can use its action to polymorph into a boar or back into\
    \ its true form, which is humanoid. Its statistics are the same in each form.\
    \ Any equipment it is wearing or carrying isn't transformed. It reverts to its\
    \ true form if it dies."
  "name": "Shapechanger"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) slashing damage."
  "name": "Clawed Gauntlet (Humanoid Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Tusk (Boar Form Only)"
"source":
- "DIP"
- "DC"
- "SDW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DIP/Anchorite%20of%20Talos.webp"
```
^statblock

```encounter-table
name: Anchorite of Talos
creatures:
 - 1: Anchorite of Talos
```