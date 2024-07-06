---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1-2
- monster/size/medium
- monster/type/undead
aliases: ["Dwarf Skeleton"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 123"
---
# [Dwarf Skeleton](2-Mechanics/CLI/bestiary/undead/dwarf-skeleton-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 123*  

```statblock
"name": "Dwarf Skeleton (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "25 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Dwarvish but can't speak"
"cr": "1/2"
"traits":
- "desc": "The skeleton has advantage on Strength and Dexterity saving throws made\
    \ against effects that make it have the [prone](/2-Mechanics/CLI/rules/conditions.md#prone)\
    \ condition."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Battleaxe"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Dwarf%20Skeleton.webp"
```
^statblock

```encounter-table
name: Dwarf Skeleton
creatures:
 - 1: Dwarf Skeleton
```