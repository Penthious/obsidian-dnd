---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/4
- monster/size/medium
- monster/type/aberration
- npc
aliases: ["Ontharyx"]
NoteIcon: npc
BestiaryType: aberration
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 115
---
# [Ontharyx](2-Mechanics/CLI/bestiary/npc/ontharyx-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 115*  

```statblock
"name": "Ontharyx (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "12"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "15"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, telepathy 60 ft."
"cr": "4"
"traits":
- "desc": "While in sunlight, Ontharyx has disadvantage on attack rolls."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Ontharyx makes two Unarmed Strike or Nightmare Blast attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 10 (3d6) psychic damage."
  "name": "Unarmed Strike"
- "desc": "Ranged Weapon Attack: +6 to hit, range 60 ft., one creature. Hit:\
    \ 7 (2d6) psychic damage, and the target must succeed on a DC 12 Wisdom saving\
    \ throw or have the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition until the start of Ontharyx's next turn."
  "name": "Nightmare Blast"
"reactions":
- "desc": "Immediately after taking damage, Ontharyx flies up to its speed. This movement\
    \ doesn't provoke opportunity attacks."
  "name": "Defensive Flight"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Ontharyx.webp"
```
^statblock

```encounter-table
name: Ontharyx
creatures:
 - 1: Ontharyx
```