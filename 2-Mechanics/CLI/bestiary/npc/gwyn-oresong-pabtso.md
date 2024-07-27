---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1-4
- monster/size/medium
- monster/type/humanoid/any-race
- npc
aliases: ["Gwyn Oresong"]
NoteIcon: npc
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 8"
---
# [Gwyn Oresong](2-Mechanics/CLI/bestiary/npc/gwyn-oresong-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 8*  

```statblock
"name": "Gwyn Oresong (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Religion": !!int "2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "any one language (usually Common), Dwarvish"
"cr": "1/4"
"traits":
- "desc": "Gwyn is a 1st-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 12, +4 to hit with spell attacks). Gwyn has following cleric spells\
    \ prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (3 slots): [bless](/2-Mechanics/CLI/spells/bless.md), [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)"
  "name": "Spellcasting"
- "desc": "Gwyn"
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Gwyn%20Oresong.webp"
```
^statblock

```encounter-table
name: Gwyn Oresong
creatures:
 - 1: Gwyn Oresong
```