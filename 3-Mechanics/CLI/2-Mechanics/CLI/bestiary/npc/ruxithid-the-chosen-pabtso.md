---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/medium
- monster/type/aberration/goblinoid
- npc
aliases: ["Ruxithid the Chosen"]
NoteIcon: npc
BestiaryType: aberration (goblinoid)
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 99"
---
# [Ruxithid the Chosen](2-Mechanics/CLI/bestiary/npc/ruxithid-the-chosen-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 99*  

Centuries ago, an abandoned duergar mining outpost called Zorzula's Rest was conquered by mind flayers, and the goblins there were exposed to the illithids' strange powers, leading a subset of the goblins to develop unusual psionic powers. The mind flayers eventually left, but the goblins remained, sequestered from the rest of the world until recently when the mind flayer fanatics called on them. Some of these goblins' descendants possess psionic powers, as evidenced by the goblin psi commanders and goblin psi brawlers (see appendix A for descriptions of both) that make up their ranks. Collectively, the goblins call themselves the Sawplees: a simplification of the word for "goblin" in the illithids' dialect of Deep Speech.

In recent weeks, the Sawplee goblins' leader found a mysterious gemstone. Unknown to Ruxithid the Chosen, a new group of mind flayer fanatics that draw power from the Far Realm planted it for him to find. The gemstone lets Ruxithid telepathically communicate with the mind flayers, who he believes are gods.

```statblock
"name": "Ruxithid the Chosen (PaBTSO)"
"size": "Medium"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "14"
- !!int "19"
- !!int "12"
- !!int "18"
- !!int "15"
- !!int "12"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "7"
"skillsaves":
  "Stealth": !!int "10"
  "Insight": !!int "5"
  "Perception": !!int "5"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Goblin, telepathy 60 ft."
"cr": "5"
"traits":
- "desc": "When Ruxithid fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
- "desc": "Ruxithid has advantage on saving throws against the [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ and [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) conditions."
  "name": "Mental Fortitude"
"actions":
- "desc": "Ruxithid makes two Psi-Charged Scimitar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage plus 7 (2d6) psychic damage."
  "name": "Psi-Charged Scimitar"
"bonus_actions":
- "desc": "Ruxithid unleashes a flurry of crystalline psychic tendrils from his brain,\
    \ targeting one creature that he can see within 30 feet of himself. The target\
    \ must succeed on a DC 15 Dexterity saving throw or take 9 (2d8) psychic damage\
    \ and have the [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) condition\
    \ until the start of Ruxithid's next turn."
  "name": "Brain Tendrils (Recharge 5-6)"
- "desc": "Ruxithid commands one allied creature he can see within 60 feet of himself\
    \ to strike. The creature can immediately use its reaction to make one melee weapon\
    \ attack against a target within its reach."
  "name": "Combat Command"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Ruxithid%20the%20Chosen.webp"
```
^statblock

```encounter-table
name: Ruxithid the Chosen
creatures:
 - 1: Ruxithid the Chosen
```