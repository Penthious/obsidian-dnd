---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/large
- monster/type/dragon/young-gem
- npc
aliases: ["Lowarnizel"]
NoteIcon: npc
BestiaryType: dragon (young gem)
SourceType: Bestiary
BookSource: Phandelver and Below: The Shattered Obelisk p. 181
---
# [Lowarnizel](2-Mechanics/CLI/bestiary/npc/lowarnizel-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 181*  

Lowarnizel is a young amethyst dragon, and his companion is a lawful neutral human mage named Gossa. Both hate the Far Realm and anything tainted by it.

```statblock
"name": "Lowarnizel (PaBTSO)"
"size": "Large"
"type": "dragon"
"subtype": "young gem"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d10 + 80"
"stats":
- !!int "21"
- !!int "12"
- !!int "21"
- !!int "18"
- !!int "15"
- !!int "19"
"speed": "40 ft., fly 80 ft. (hover), swim 40 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
  "Constitution": !!int "9"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "10"
  "Arcana": !!int "12"
  "Persuasion": !!int "8"
"damage_resistances": "force, psychic"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 20"
"languages": "Common, Draconic, telepathy 120 ft."
"cr": "9"
"traits":
- "desc": "Lowarnizel casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n1/day\
    \ each: [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [haste](/2-Mechanics/CLI/spells/haste.md),\
    \ [protection from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
    \ [sending](/2-Mechanics/CLI/spells/sending.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "Lowarnizel can breathe both air and water."
  "name": "Amphibious"
"actions":
- "desc": "Lowarnizel makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d10 + 5) piercing damage plus 4 (1d8) force damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) slashing damage."
  "name": "Claw"
- "desc": "Lowarnizel creates a shining bead of gravitational force, then releases\
    \ the energy in a 30-foot cone. Each creature in that area must make a DC 17 Strength\
    \ saving throw. On a failed save, a creature takes 36 (8d8) force damage, and\
    \ its speed becomes 0 until the start of the dragon's next turn. On a successful\
    \ save, a creature takes half as much damage only."
  "name": "Singularity Breath (Recharge 5-6)"
"bonus_actions":
- "desc": "Lowarnizel magically transforms into any creature that is Medium or Small,\
    \ while retaining his game statistics (other than his size). This transformation\
    \ ends if the dragon is reduced to 0 hit points or uses a bonus action to end\
    \ it."
  "name": "Change Shape"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Lowarnizel.webp"
```
^statblock

```encounter-table
name: Lowarnizel
creatures:
 - 1: Lowarnizel
```