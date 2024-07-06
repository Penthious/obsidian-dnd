---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/large
- monster/type/aberration
aliases: ["Oculorb"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 214
---
# [Oculorb](2-Mechanics/CLI/bestiary/aberration/oculorb-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 214*  

Many oculorbs are dreamed into existence by beholders. The Far Realm's strange power can pervade a beholder's dreams, resulting in the birth of an oculorb.

Oculorbs resemble a slimy conglomeration of eyes in many sizes and shapes. They are dreaded even by the beholders that birth them. An oculorb is a tangle of negative emotions—the fury, melancholy, and obsession of its creator, all given gruesome, corporeal form. Like a beholder, an oculorb can fire beams of energy from its eyes, but an oculorb's eyes lack the more sophisticated magical nature of a beholder's eyestalks. Instead, an oculorb unleashes powerful waves of energy charged with negative emotions, cowing its foes with despair and ire.

```statblock
"name": "Oculorb (PaBTSO)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"stats":
- !!int "13"
- !!int "10"
- !!int "17"
- !!int "14"
- !!int "15"
- !!int "19"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "6"
  "Intelligence": !!int "6"
"skillsaves":
  "Investigation": !!int "6"
  "Perception": !!int "10"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "truesight 60 ft., passive Perception 20"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "9"
"traits":
- "desc": "The oculorb has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The oculorb has advantage on initiative rolls and can't be surprised."
  "name": "Watchful Eyes"
"actions":
- "desc": "The oculorb makes two Dreadful Contact attacks or four Eye Beam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 14\
    \ (3d6 + 4) psychic damage, or 25 (6d6 + 4) psychic damage if the target has\
    \ the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) condition."
  "name": "Dreadful Contact"
- "desc": "Ranged Spell Attack: +8 to hit, range 120 ft., one creature. Hit:\
    \ 14 (3d6 + 4) psychic damage."
  "name": "Eye Beam"
- "desc": "The oculorb releases a wave of negative emotions, choosing one of the following\
    \ options:"
  "name": "Antipathic Flood (Recharge 5-6)"
- "desc": "The oculorb weeps, releasing a wave of crushing despair. Each creature\
    \ within 30 feet of the oculorb must make a DC 16 Constitution saving throw. On\
    \ a failed save, a creature's speed is reduced to 0 feet until the end of the\
    \ oculorb's next turn, and if the creature was concentrating, its [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ is broken."
  "name": "Weeping Eyes"
- "desc": "The oculorb's eyes unleash furious scarlet energy in a 60-foot cone. Each\
    \ creature in that area must make a DC 16 Wisdom saving throw. On a failed save,\
    \ a creature takes 33 (6d10) necrotic damage and has the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition for 1 minute. On a successful save, a creature takes half as much\
    \ damage and isn't [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened).\
    \ A [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) creature can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a successful save."
  "name": "Withering Glare"
"reactions":
- "desc": "When the oculorb is damaged by a creature it can see within 60 feet of\
    \ itself, it forces the creature to make a DC 16 Wisdom saving throw. The creature\
    \ takes 10 (3d6) psychic damage on a failed save, or half as much damage on\
    \ a successful one."
  "name": "Obsessive Rebuke"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Oculorb.webp"
```
^statblock

```encounter-table
name: Oculorb
creatures:
 - 1: Oculorb
```