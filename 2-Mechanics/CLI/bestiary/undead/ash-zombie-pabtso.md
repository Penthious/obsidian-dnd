---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
aliases: ["Ash Zombie"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 52"
---
# [Ash Zombie](2-Mechanics/CLI/bestiary/undead/ash-zombie-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 52*  

```statblock
"name": "Ash Zombie (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
  "name": "Undead Fortitude"
- "desc": "When the zombie dies, it leaves a cloud of ash that lasts for 5 minutes\
    \ but does not obscure vision."
  "name": "Ash Cloud"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Slam"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Ash%20Zombie.webp"
```
^statblock

```encounter-table
name: Ash Zombie
creatures:
 - 1: Ash Zombie
```