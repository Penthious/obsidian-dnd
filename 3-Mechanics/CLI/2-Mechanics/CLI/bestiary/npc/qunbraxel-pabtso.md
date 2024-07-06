---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/medium
- monster/type/aberration/mind-flayer
- monster/type/aberration/warlock
aliases: ["Qunbraxel"]
NoteIcon: monster
BestiaryType: aberration (mind flayer, warlock)
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 135
---
# [Qunbraxel](2-Mechanics/CLI/bestiary/npc/qunbraxel-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 135*  

Qunbraxel is an arrogant mind flayer warlock. Qunbraxel is always attended by four loyal grimlocks. They swap this duty with other grimlocks nearby, although Qunbraxel can hardly be bothered to tell one grimlock minion from another.

Cut off from any elder brain Qunbraxel considers worthy, the mind flayer hopes to join the Ilvaash fanatics and receive power and insight from the Far Realm.

```statblock
"name": "Qunbraxel (PaBTSO)"
"size": "Medium"
"type": "aberration"
"subtype": "mind flayer, warlock"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "11"
- !!int "14"
- !!int "17"
- !!int "19"
- !!int "15"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "6"
  "Intelligence": !!int "8"
"skillsaves":
  "Stealth": !!int "6"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "8"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Deep Speech, telepathy 60 ft., Undercommon"
"cr": "9"
"traits":
- "desc": "Qunbraxel casts one of the following spells, requiring no spell components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\
    \ (self only), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md) (the hand is\
    \ invisible), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1/day each: [dominate monster](/2-Mechanics/CLI/spells/dominate-monster.md),\
    \ [plane shift](/2-Mechanics/CLI/spells/plane-shift.md) (self only)\n\n2/day\
    \ each: [confusion](/2-Mechanics/CLI/spells/confusion.md), [sending](/2-Mechanics/CLI/spells/sending.md),\
    \ [telekinesis](/2-Mechanics/CLI/spells/telekinesis.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "Qunbraxel has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack\
    \ and one Tentacle attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 15\
    \ (2d10 + 4) psychic damage. If the target is Medium or smaller, it has the\
    \ [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) condition (escape\
    \ DC 16) and must succeed on a DC 16 Intelligence saving throw or have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ condition until the grapple ends."
  "name": "Tentacle"
- "desc": "Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit: 20\
    \ (3d10 + 4) force damage."
  "name": "Eldritch Bolt"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one Humanoid with the\
    \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) condition who is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ by Qunbraxel. Hit: 55 (10d10) piercing damage. If this damage reduces the\
    \ target to 0 hit points, Qunbraxel kills it by extracting and devouring its brain."
  "name": "Extract Brain"
- "desc": "Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature\
    \ in that area must succeed on a DC 16 Intelligence saving throw or take 26 (5d8\
    \ + 4) psychic damage and have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ condition for 1 minute. A [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Mind Blast (Recharge 5-6)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Qunbraxel.webp"
```
^statblock

```encounter-table
name: Qunbraxel
creatures:
 - 1: Qunbraxel
```