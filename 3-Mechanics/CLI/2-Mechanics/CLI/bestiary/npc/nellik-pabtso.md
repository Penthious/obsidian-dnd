---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/large
- monster/type/fiend/yugoloth
aliases: ["Nellik"]
NoteIcon: monster
BestiaryType: fiend (yugoloth)
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 193
---
# [Nellik](2-Mechanics/CLI/bestiary/npc/nellik-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 193*  

```statblock
"name": "Nellik (PaBTSO)"
"size": "Large"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "123"
"hit_dice": "13d10 + 52"
"stats":
- !!int "20"
- !!int "11"
- !!int "19"
- !!int "12"
- !!int "10"
- !!int "15"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Intimidation": !!int "6"
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "9"
"traits":
- "desc": "Nellik's innate spellcasting ability is Charisma. Nellik can innately cast\
    \ the following spells, requiring no material components:\n\nAt will: [darkness](/2-Mechanics/CLI/spells/darkness.md),\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md) (self only), [mirror\
    \ image](/2-Mechanics/CLI/spells/mirror-image.md)"
  "name": "Innate Spellcasting"
- "desc": "Nellik has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Nellik's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "Nellik makes two melee attacks, or it makes one melee attack and teleports\
    \ before or after the attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage. If the target is a creature, it must succeed on\
    \ a DC 16 Constitution saving throw or take 5 (2d4) slashing damage at the start\
    \ of each of its turns due to a fiendish wound. Each time Nellik hits the wounded\
    \ target with this attack, the damage dealt by the wound increases by 5 (2d4).\
    \ Any creature can take an action to stanch the wound with a successful DC 13\
    \ Wisdom ([Medicine](/2-Mechanics/CLI/rules/skills.md#Medicine)) check. The wound\
    \ also closes if the target receives magical healing."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 19\
    \ (2d12 + 6) slashing damage; if the target is an Aberration, it takes an additional\
    \ 6 (1d12) slashing damage, and if it is grappling a creature, it must succeed\
    \ on a DC 15 Strength saving throw or its grapple ends."
  "name": "Greataxe"
- "desc": "Nellik magically teleports, along with any equipment it is wearing or carrying,\
    \ up to 60 feet to an unoccupied space it can see."
  "name": "Teleport"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Nellik.webp"
```
^statblock

```encounter-table
name: Nellik
creatures:
 - 1: Nellik
```