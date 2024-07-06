---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/2
- monster/size/small
- monster/type/aberration/goblinoid
aliases: ["Goblin Psi Brawler"]
NoteIcon: monster
BestiaryType: aberration (goblinoid)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 215"
---
# [Goblin Psi Brawler](2-Mechanics/CLI/bestiary/aberration/goblin-psi-brawler-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 215*  

Goblin psi brawlers use their psionic talents to heighten their physical might. Their strikes crackle with psychic energy, and while angered, goblin psi brawlers can unleash a telekinetic thrust strong enough to knock enemies to the ground.

## Psionic Goblins

The specifics of how a psionic goblin comes to exist vary. Some are born, changed by energy leaking from the Far Realm. Others transform themselves with their psionic power or enter into agreements with other Aberrations, which help them transform in return for their service as shock troops. Regardless, the result is the same: a goblin with unnatural and barely contained psychic power.

Psionic goblins often struggle to handle the turbulent psychic energy within their minds and bodies. Those psionic goblins who learn how to safely tap into this psychic power are formidable forces in combat. Psionic goblins often augment their martial skills with telekinesis, and stealthy squads of psionic goblin warriors can communicate via telepathy, making them excellent infiltrators and ambushers.

```statblock
"name": "Goblin Psi Brawler (PaBTSO)"
"size": "Small"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[studded leather armor](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "31"
"hit_dice": "7d6 + 7"
"stats":
- !!int "9"
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Stealth": !!int "7"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin, telepathy 30 ft."
"cr": "2"
"traits":
- "desc": "When the goblin dies, its pent-up mental energy explodes in a psychic blast.\
    \ Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving\
    \ throw or take 5 (2d4) psychic damage."
  "name": "Mental Burst"
- "desc": "The goblin has advantage on saving throws against effects that would make\
    \ it have the [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition."
  "name": "Mental Fortitude"
"actions":
- "desc": "The goblin makes two Unarmed Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage plus 3 (1d6) psychic damage."
  "name": "Unarmed Strike"
"bonus_actions":
- "desc": "The goblin takes the Disengage or Hide action."
  "name": "Nimble Escape"
- "desc": "The goblin targets one creature it can see within 30 feet of itself with\
    \ a thrust of telekinetic force. The target must succeed on a DC 13 Strength saving\
    \ throw or have the [prone](/2-Mechanics/CLI/rules/conditions.md#prone) condition."
  "name": "Telekinetic Shove"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Goblin%20Psi%20Brawler.webp"
```
^statblock

```encounter-table
name: Goblin Psi Brawler
creatures:
 - 1: Goblin Psi Brawler
```