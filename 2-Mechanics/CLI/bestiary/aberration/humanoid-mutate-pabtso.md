---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pabtso
- monster/cr/4
- monster/size/medium
- monster/type/aberration
aliases: ["Humanoid Mutate"]
NoteIcon: monster
BestiaryType: aberration
SourceType: Bestiary
BookSource: "Phandelver and Below: The Shattered Obelisk p. 212"
---
# [Humanoid Mutate](2-Mechanics/CLI/bestiary/aberration/humanoid-mutate-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 212*  

When the influence of the Far Realm affects Humanoids, the resulting creature might be a thing of nightmares. Multitudinous webbed wings sprout haphazardly along this mutate's body. Its skin becomes clammy and as smooth as a salamander's.

Some intelligent Humanoid mutates retain their personalities from before they were exposed to the Far Realm. Some, driven by the allure of otherworldly powers, seek this transformation to become malevolent prophets and harbingers. Others find magical ways to return to their previous forms.

## Mutates

A creature exposed to the strange energy of the Far Realm risks developing mutations. Such a creature undergoes a metamorphosis as the powers of the Far Realm rewrite the fundamentals of the creature's existence.

Any creature can become a mutate and transform to exhibit physical characteristics associated with the Far Realm. Some creatures become mutates after prolonged exposure to Far Realm energy or magic drawn from that strange plane. Others deliberately change themselves, seeking to embrace the fell powers they worship. Creatures that become mutates often inexplicably change back to their previous forms once the Far Realm influence abates.

Forcing a transformation on creatures inexplicably fails, though evil forces—such as the mind flayer empire of old—have conducted much research on the topic. For centuries, mind flayers have tried to create armies of mutates to sweep through the Underdark. However, their efforts always proved fruitless, and eventually the mind flayers gave up their schemes.

Several common types of mutates exist. The individuals with stat blocks presented in this section are found in the preceding adventure, although other mutates exist. Some creatures are more prone to becoming Far Realm mutates, such as the cloaker and otyugh.

Mutates often gain psionic abilities, grow wings, become covered in otherworldly slime, or exhibit other unsettling traits. Specific mutated creatures are further described in appendix A.

```statblock
"name": "Humanoid Mutate (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "12"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "15"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "psychic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, telepathy 60 ft."
"cr": "4"
"traits":
- "desc": "While in sunlight, the mutate has disadvantage on attack rolls."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The mutate makes two Unarmed Strike or Nightmare Blast attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 10 (3d6) psychic damage."
  "name": "Unarmed Strike"
- "desc": "Ranged Weapon Attack: +6 to hit, range 60 ft., one creature. Hit:\
    \ 7 (2d6) psychic damage, and the target must succeed on a DC 12 Wisdom saving\
    \ throw or have the [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ condition until the start of the mutate's next turn."
  "name": "Nightmare Blast"
"reactions":
- "desc": "Immediately after taking damage, the mutate flies up to its speed. This\
    \ movement doesn't provoke opportunity attacks."
  "name": "Defensive Flight"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PaBTSO/Humanoid%20Mutate.webp"
```
^statblock

```encounter-table
name: Humanoid Mutate
creatures:
 - 1: Humanoid Mutate
```