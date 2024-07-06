---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Psionic Ashenwight"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 204"
---
# [Psionic Ashenwight](2-Mechanics/CLI/bestiary/undead/psionic-ashenwight-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 204*  

When an ashenwight arises near a crystal vein infused with aberrant power, or when one lingers in an area of fell magic, there is a chance for the ashenwight to develop psionic abilities. A psionic ashenwight is markedly more sapient than other ashenwights, though the resulting consciousness is a new creation separate from who the ashenwight was in life.

Some psionic ashenwights dedicate their existence to piecing together their previous life, while others strive to enlighten other ashenwights to this new psionic power.

## Ashenwights

When a Humanoid consumed by cruelty and rage dies in an area corrupted by the Far Realm, the creature sometimes rises as an ashenwight. The skin of these Undead horrors is desiccated, and their eyes often glow with otherworldly power.

```statblock
"name": "Psionic Ashenwight (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "19"
- !!int "13"
- !!int "15"
- !!int "17"
- !!int "14"
- !!int "6"
"speed": "25 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "6"
  "Strength": !!int "7"
  "Constitution": !!int "5"
"damage_resistances": "necrotic, poison, psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "passive Perception 12"
"languages": "telepathy 120 ft., understands the languages it knew in life but can't\
  \ speak"
"cr": "7"
"traits":
- "desc": "The ashenwight casts one of the following spells, requiring no spellcasting\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 14):\n\nAt will: [mage hand](/2-Mechanics/CLI/spells/mage-hand.md) (the\
    \ hand is invisible)\n\n1/day: [calm emotions](/2-Mechanics/CLI/spells/calm-emotions.md)"
  "name": "Spellcasting (Psionics)"
"actions":
- "desc": "The ashenwight makes two Necrotic Shard attacks. It also uses Psionic Crown\
    \ if available."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 7 (1d6 + 4) piercing damage plus 9 (2d8) necrotic damage.\
    \ If the target is a creature, it has disadvantage on the next attack roll it\
    \ makes before the end of its next turn."
  "name": "Necrotic Shard"
- "desc": "The ashenwight wreathes the head of a creature it can see within 60 feet\
    \ of itself with a crown of jagged, spectral crystals. The target must succeed\
    \ on a DC 14 Wisdom saving throw or have the [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ condition for 1 minute. While [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ in this way, the target's thoughts are sluggish; it can't take reactions, its\
    \ speed is halved, and it takes 9 (2d8) psychic damage at the start of each\
    \ of its turns. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Psionic Crown (Recharge 5-6)"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Psionic%20Ashenwight.webp"
```
^statblock

```encounter-table
name: Psionic Ashenwight
creatures:
 - 1: Psionic Ashenwight
```