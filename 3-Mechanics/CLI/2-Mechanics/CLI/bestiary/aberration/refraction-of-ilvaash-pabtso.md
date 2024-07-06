---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/15
- monster/size/huge
- monster/type/aberration/mind-flayer
aliases: ["Refraction of Ilvaash"]
NoteIcon: monster
BestiaryType: aberration (mind flayer)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 197"
---
# [Refraction of Ilvaash](2-Mechanics/CLI/bestiary/aberration/refraction-of-ilvaash-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 197*  

Ilvaash was formed from the remains of the mind flayer god Ilsensine, the God-Brain. When Ilsensine left the Far Realm to establish a divine domain elsewhere, pieces of the God-Brain sloughed away and awoke to sentience. This is Ilvaash, the Dissonant Psyche.

The refraction of Ilvaash wields only a sliver of the godlet's power but is nevertheless a formidable foe.

```statblock
"name": "Refraction of Ilvaash (PaBTSO)"
"size": "Huge"
"type": "aberration"
"subtype": "mind flayer"
"alignment": "Lawful Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "21d12 + 63"
"stats":
- !!int "17"
- !!int "10"
- !!int "17"
- !!int "23"
- !!int "20"
- !!int "22"
"speed": "10 ft., fly 30 ft. (hover), swim 10 ft."
"saves":
  "Wisdom": !!int "10"
  "Intelligence": !!int "11"
"skillsaves":
  "Intimidation": !!int "11"
  "Insight": !!int "15"
  "Arcana": !!int "11"
  "Persuasion": !!int "11"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "blindsight 120 ft., passive Perception 15"
"languages": "Common, Deep Speech, telepathy 100 miles, Undercommon"
"cr": "15"
"traits":
- "desc": "The refraction casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 19):\n\nAt\
    \ will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md)\n\
    \n1/day each: [feeblemind](/2-Mechanics/CLI/spells/feeblemind.md), [plane\
    \ shift](/2-Mechanics/CLI/spells/plane-shift.md) (self only)\n\n3/day each:\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [modify memory](/2-Mechanics/CLI/spells/modify-memory.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "The refraction is aware of creatures within 100 miles of it that have an\
    \ Intelligence score of 4 or higher. It knows the distance and direction to each\
    \ creature, as well as each one's Intelligence score, but can't sense anything\
    \ else about it. A creature protected by a [mind blank](/2-Mechanics/CLI/spells/mind-blank.md)\
    \ spell, a [nondetection](/2-Mechanics/CLI/spells/nondetection.md) spell, or similar\
    \ magic can't be perceived in this manner."
  "name": "Creature Sense"
- "desc": "The refraction can move through other creatures and objects as if they\
    \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
    \ inside an object."
  "name": "Incorporeal Movement"
- "desc": "If the refraction fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (5/Day)"
- "desc": "The refraction has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The refraction makes two Dissonant Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft. or range 120 ft., one\
    \ creature. Hit: 25 (3d12 + 6) psychic damage. If the target is a creature\
    \ concentrating on a spell, its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ is broken."
  "name": "Dissonant Claw"
- "desc": "Creatures of the refraction's choice within 60 feet of it must succeed\
    \ on a DC 19 Intelligence saving throw or take 33 (5d10 + 6) psychic damage\
    \ and have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) condition\
    \ for 1 minute. A [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) creature\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Mind Blast (Recharge 5-6)"
- "desc": "The refraction teleports, along with any equipment it is wearing or carrying,\
    \ up to 120 feet to an unoccupied place that it can see."
  "name": "Teleport"
"legendary_actions":
- "desc": "The refraction targets a creature within 120 feet of itself and disrupts\
    \ its mental processes, causing the target to have disadvantage on all ability\
    \ checks, attack rolls, and saving throws until the end of the target's next turn."
  "name": "Mindbreaker"
- "desc": "The refraction makes one Dissonant Claw attack."
  "name": "Projected Claw (Costs 2 Actions)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Refraction%20of%20Ilvaash.webp"
```
^statblock

```encounter-table
name: Refraction of Ilvaash
creatures:
 - 1: Refraction of Ilvaash
```