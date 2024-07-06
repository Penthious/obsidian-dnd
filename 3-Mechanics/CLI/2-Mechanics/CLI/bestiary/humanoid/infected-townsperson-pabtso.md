---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Infected Townsperson"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 139"
---
# [Infected Townsperson](2-Mechanics/CLI/bestiary/humanoid/infected-townsperson-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 139*  

```statblock
"name": "Infected Townsperson (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Chaotic alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "16"
- !!int "12"
- !!int "17"
- !!int "9"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
- "desc": "At the start of its turn, the townsperson can gain advantage on all melee\
    \ weapon attack rolls during that turn, but attack rolls against it have advantage\
    \ until the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage plus 3 (1d6) psychic damage."
  "name": "Psychic Slam"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Infected%20Townsperson.webp"
```
^statblock

```encounter-table
name: Infected Townsperson
creatures:
 - 1: Infected Townsperson
```