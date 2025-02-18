---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/large
- monster/type/plant
aliases: ["Psionic Shambling Mound"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 108"
---
# [Psionic Shambling Mound](2-Mechanics/CLI/bestiary/plant/psionic-shambling-mound-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 108*  

```statblock
"name": "Psionic Shambling Mound (PaBTSO)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  "Stealth": !!int "2"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened), [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The shambling mound casts one of the following spells, requiring no spell\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 8):\n\nAt will: [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\
    \n1/day: [charm person](/2-Mechanics/CLI/spells/charm-person.md) (already\
    \ cast)"
  "name": "Spellcasting (Psionics)"
- "desc": "Whenever the shambling mound is subjected to lightning damage, it takes\
    \ no damage and regains a number of hit points equal to the lightning damage dealt."
  "name": "Lightning Absorption"
"actions":
- "desc": "The shambling mound makes two slam attacks. If both attacks hit a Medium\
    \ or smaller target, the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14), and the shambling mound uses its Engulf on it."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "The shambling mound engulfs a Medium or smaller creature [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by it. The engulfed target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained), and unable to\
    \ breathe, and it must succeed on a DC 14 Constitution saving throw at the start\
    \ of each of the mound's turns or take 13 (2d8 + 4) bludgeoning damage. If the\
    \ mound moves, the engulfed target moves with it. The mound can have only one\
    \ creature engulfed at a time."
  "name": "Engulf"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Psionic%20Shambling%20Mound.webp"
```
^statblock

```encounter-table
name: Psionic Shambling Mound
creatures:
 - 1: Psionic Shambling Mound
```