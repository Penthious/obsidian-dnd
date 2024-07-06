---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/11
- monster/size/medium
- monster/type/aberration
aliases: ["Mind Flayer Clairvoyant"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 209
---
# [Mind Flayer Clairvoyant](2-Mechanics/CLI/bestiary/aberration/mind-flayer-clairvoyant-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 209*  

In pursuit of reconstructing their lost empire, a few mind flayers have turned to their home plane, the Far Realm, for answers. A mind flayer clairvoyant has peered into that realm's starless depths and been subsequently rewarded with extraordinary powers.

Instead of heeding an elder brain, a mind flayer clairvoyant listens to the whispers and whims of the voices of the Far Realm. In addition to feasting on brains, a mind flayer clairvoyant can summon tentacles that rip through the fabric of reality and distort the minds of enemies.

## Mind Flayers

Mind flayers, also known as illithids, feast on the brains of Humanoids across the multiverse. They are distinguished by their purple-toned skin and octopus-like heads, from which extend writhing tentacles.

```statblock
"name": "Mind Flayer Clairvoyant (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "[breastplate](/2-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"stats":
- !!int "11"
- !!int "12"
- !!int "15"
- !!int "21"
- !!int "17"
- !!int "18"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "7"
  "Intelligence": !!int "9"
"skillsaves":
  "Stealth": !!int "5"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Arcana": !!int "9"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., truesight 15 ft., passive Perception 17"
"languages": "Deep Speech, telepathy 120 ft., Undercommon"
"cr": "11"
"traits":
- "desc": "The mind flayer casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 17):\n\nAt\
    \ will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)\n\n\
    1/day: [plane shift](/2-Mechanics/CLI/spells/plane-shift.md) (self only)\n\
    \n3/day each: [clairvoyance](/2-Mechanics/CLI/spells/clairvoyance.md) (as\
    \ an action), [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "If the mind flayer fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The mind flayer has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The mind flayer makes two Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 21\
    \ (3d10 + 5) psychic damage. If the target is Medium or smaller, it has the\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) condition (escape\
    \ DC 17) and must succeed on a DC 17 Intelligence saving throw or have the [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ condition until the grapple ends."
  "name": "Tentacle"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ Humanoid [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) by the mind\
    \ flayer. Hit: 55 (10d10) piercing damage. If this damage reduces the target\
    \ to 0 hit points, the mind flayer kills it by extracting and devouring its brain."
  "name": "Extract Brain"
- "desc": "The mind flayer opens a rift into the Far Realm, centered on a point the\
    \ mind flayer can see within 60 feet of itself, and a tentacle lashes across creatures\
    \ near the rift. Each creature other than mind flayers within 30 feet of the rift\
    \ must make a DC 17 Intelligence saving throw, after which the tentacle disappears\
    \ and the rift closes. On a failed save, a creature takes 18 (4d8) cold damage\
    \ from the rift plus 18 (4d8) psychic damage from the tentacle and has the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ condition for 1 minute. On a successful save, a creature takes half as much\
    \ damage only. A [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) creature\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Unleash Void (Recharge 5-6)"
"reactions":
- "desc": "When hit by an attack roll, the mind flayer gains a +4 bonus to its AC\
    \ against that attack roll, potentially causing it to miss. Then the mind flayer,\
    \ along with any equipment it is wearing or carrying, magically teleports up to\
    \ 60 feet to an unoccupied space it can see."
  "name": "Warp Reality"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Mind%20Flayer%20Clairvoyant.webp"
```
^statblock

```encounter-table
name: Mind Flayer Clairvoyant
creatures:
 - 1: Mind Flayer Clairvoyant
```