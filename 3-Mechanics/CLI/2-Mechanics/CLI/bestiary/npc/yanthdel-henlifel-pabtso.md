---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
- npc
aliases: ["Yanthdel Henlifel"]
NoteIcon: npc
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 114"
---
# [Yanthdel Henlifel](2-Mechanics/CLI/bestiary/npc/yanthdel-henlifel-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 114*  

```statblock
"name": "Yanthdel Henlifel (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "4"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
- "desc": "Yanthdel's spellcasting ability is Charisma (spell save DC 12). It can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only)"
  "name": "Innate Spellcasting"
- "desc": "Yanthdel has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put Yanthdel to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Yanthdel has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Yanthdel makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage plus 10 (3d6) poison damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. Hit:\
    \ 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ while [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way.\
    \ The target wakes up if it takes damage or if another creature takes an action\
    \ to shake it awake."
  "name": "Hand Crossbow"
"reactions":
- "desc": "Yanthdel adds 3 to its AC against one melee attack that would hit it. To\
    \ do so, Yanthdel must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Yanthdel%20Henlifel.webp"
```
^statblock

```encounter-table
name: Yanthdel Henlifel
creatures:
 - 1: Yanthdel Henlifel
```