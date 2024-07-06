---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/8
- monster/size/small
- monster/type/aberration
aliases: ["Intellect Snare"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 208
---
# [Intellect Snare](2-Mechanics/CLI/bestiary/aberration/intellect-snare-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 208*  

When the strange horrors of the Far Realm rip at the minds of individuals, some of those wayward shreds of thought conglomerate to form an intellect snare. An intellect snare appears as a writhing ball of tentacles, echoing with the cacophonous sounds of every thought the snare has consumed.

Intellect snares are scavengers, often found scouring the aftermath of a mind flayer attack to feast on whatever hapless creatures are left behind. An intellect snare feeds by wrapping a creature in one of its tentacles and then siphoning shreds of thought, leaving a tattered mind in its wake.

```statblock
"name": "Intellect Snare (PaBTSO)"
"size": "Small"
"type": "aberration"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "99"
"hit_dice": "18d6 + 36"
"stats":
- !!int "13"
- !!int "18"
- !!int "15"
- !!int "23"
- !!int "17"
- !!int "11"
"speed": "0 ft., fly 45 ft. (hover)"
"saves":
  "Charisma": !!int "3"
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"damage_immunities": "psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 120 ft. (can't see beyond this radius), passive Perception 13"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "Any creature that starts its turn within 30 feet of the intellect snare\
    \ must succeed on a DC 17 Wisdom saving throw or have the [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ condition for 1 minute. An [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ creature can repeat the saving throw at the start of each of its turns, ending\
    \ the effect on itself on a success. A creature that succeeds on the saving throw\
    \ is immune to this intellect snare's Cacophony of Minds for 24 hours."
  "name": "Cacophony of Minds"
- "desc": "The intellect snare has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The intellect snare makes two Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 10\
    \ (1d8 + 6) force damage, and if the target is a Medium or smaller creature,\
    \ the target has the [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ condition (escape DC 17)."
  "name": "Tentacle"
"bonus_actions":
- "desc": "The intellect snare targets one creature it is grappling. The target must\
    \ make a DC 17 Intelligence saving throw, taking 21 (6d6) psychic damage on\
    \ a failed save, or half as much damage on a successful one. The intellect snare\
    \ then regains a number of hit points equal to the amount of damage taken."
  "name": "Siphon Thoughts"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Intellect%20Snare.webp"
```
^statblock

```encounter-table
name: Intellect Snare
creatures:
 - 1: Intellect Snare
```