---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
aliases: ["Iarno "Glasstaff" Albrek"]
NoteIcon: monster
BestiaryType: humanoid (human, wizard)
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 43
---
# [Iarno "Glasstaff" Albrek](2-Mechanics/CLI/bestiary/npc/iarno-glasstaff-albrek-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 43*  

A former member of the Lords' Alliance, Glasstaff seized an opportunity in Phandalin to line his own pockets. Originally tasked with setting up a constabulary, he instead assembled a group of outlaws and local ruffians to secure his own position in town.

Glasstaff puts on airs of gentility and courteous manners, addressing his bandits and ruffians as "my good fellows," and referring to sordid acts such as kidnapping or arson as "that unpleasant little business" or "those unfortunate events." He may refer to the characters as his "honored guests," and expresses regret that he cannot provide suitable entertainment for the occasion of their visit. Beneath his genteel demeanor, however, Glasstaff is just as violent and arrogant as any of the Redbrands.

```statblock
"name": "Iarno \"Glasstaff\" Albrek (PaBTSO)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "16 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md) and [staff\
  \ of defense](/2-Mechanics/CLI/items/staff-of-defense-pabtso.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "5"
"skillsaves":
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
- "desc": "Glasstaff casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\nAt\
    \ will: [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md)\n\
    \n1/day each: [charm person](/2-Mechanics/CLI/spells/charm-person.md), [hold\
    \ person](/2-Mechanics/CLI/spells/hold-person.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)"
  "name": "Spellcasting"
- "desc": "Glasstaff wields a [staff of defense](/2-Mechanics/CLI/items/staff-of-defense-pabtso.md)\
    \ (see appendix B). With the staff in hand, he can use an action to cast the [mage\
    \ armor](/2-Mechanics/CLI/spells/mage-armor.md) spell and use his reaction to\
    \ cast the [shield](/2-Mechanics/CLI/spells/shield.md) spell."
  "name": "Special Equipment"
"actions":
- "desc": "Glasstaff makes two Shocking Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 6 (1d6 + 3) lightning damage."
  "name": "Shocking Burst"
"bonus_actions":
- "desc": "Glasstaff magically teleports, along with any equipment he is wearing or\
    \ carrying, up to 30 feet to an unoccupied space he can see."
  "name": "Teleport (2/Day)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Iarno%20Glasstaff%20Albrek.webp"
```
^statblock

```encounter-table
name: Iarno "Glasstaff" Albrek
creatures:
 - 1: Iarno "Glasstaff" Albrek
```