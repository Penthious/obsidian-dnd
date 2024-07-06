---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/8
- monster/size/medium
- monster/type/aberration
aliases: ["Mind Flayer Prophet"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 210"
---
# [Mind Flayer Prophet](2-Mechanics/CLI/bestiary/aberration/mind-flayer-prophet-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 210*  

Some mind flayers dedicate their lives to channeling abstruse truths from beyond reality. This insight gives them preternatural senses and allows them to focus their innate psionic power.

## Mind Flayers

Mind flayers, also known as illithids, feast on the brains of Humanoids across the multiverse. They are distinguished by their purple-toned skin and octopus-like heads, from which extend writhing tentacles.

```statblock
"name": "Mind Flayer Prophet (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "20"
- !!int "17"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "6"
  "Intelligence": !!int "8"
"skillsaves":
  "Stealth": !!int "5"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "8"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Deep Speech, telepathy 120 ft., Undercommon"
"cr": "8"
"traits":
- "desc": "The mind flayer casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\nAt\
    \ will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md)\n\n1/day each: [dominate\
    \ monster](/2-Mechanics/CLI/spells/dominate-monster.md), [plane shift](/2-Mechanics/CLI/spells/plane-shift.md)\
    \ (self only), [true seeing](/2-Mechanics/CLI/spells/true-seeing.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "The mind flayer has advantage on initiative rolls and can't be surprised\
    \ as long as it doesn't have the [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ condition."
  "name": "Awareness"
- "desc": "The mind flayer has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 16\
    \ (2d10 + 5) psychic damage. If the target is Medium or smaller, it has the\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) condition (escape\
    \ DC 16) and must succeed on a DC 16 Intelligence saving throw or have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ condition until the grapple ends."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one Humanoid [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by the mind flayer. Hit: 55 (10d10) piercing damage. If this damage reduces\
    \ the target to 0 hit points, the mind flayer kills it by extracting and devouring\
    \ its brain."
  "name": "Extract Brain"
- "desc": "The mind flayer lashes out with psychic energy, targeting up to two creatures\
    \ it can see within 60 feet of itself. Each target must succeed on a DC 16 Intelligence\
    \ saving throw or take 23 (4d8 + 5) psychic damage and have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ condition for 1 minute. A [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success."
  "name": "Mind Whip (Recharge 5-6)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Mind%20Flayer%20Prophet.webp"
```
^statblock

```encounter-table
name: Mind Flayer Prophet
creatures:
 - 1: Mind Flayer Prophet
```