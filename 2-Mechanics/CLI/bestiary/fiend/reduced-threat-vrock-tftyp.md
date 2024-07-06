---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/6
- monster/size/large
- monster/type/fiend/demon
aliases: ["Reduced-Threat Vrock"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: "Tales from the Yawning Portal p. 113"
---
# [Reduced-Threat Vrock](2-Mechanics/CLI/bestiary/fiend/reduced-threat-vrock-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Vrock (TftYP)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"stats":
- !!int "17"
- !!int "15"
- !!int "18"
- !!int "8"
- !!int "13"
- !!int "8"
"speed": "40 ft., fly 60 ft."
"saves":
  "Charisma": !!int "2"
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Abyssal, telepathy 120 ft."
"cr": "6"
"traits":
- "desc": "The vrock has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The vrock makes two attacks: one with its beak and one with its talons."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d10 + 3) slashing damage."
  "name": "Talons"
- "desc": "A 15-foot-radius cloud of toxic spores extends out from the vrock. The\
    \ spores spread around corners. Each creature in that area must succeed on a DC\
    \ 14 Constitution saving throw or become [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned).\
    \ While [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) in this way,\
    \ a target takes 5 (1d10) poison damage at the start of each of its turns. A\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success. Emptying a vial of holy water on the target also\
    \ ends the effect on it."
  "name": "Spores (Recharge 6)"
- "desc": "The vrock emits a horrific screech. Each creature within 20 feet of it\
    \ that can hear it and that isn't a demon must succeed on a DC 14 Constitution\
    \ saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) until\
    \ the end of the vrock's next turn."
  "name": "Stunning Screech (1/Day)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Vrock.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Vrock
creatures:
 - 1: Reduced-Threat Vrock
```