---
questObtained: 
questStatus: Ready for party
questGiver: "[[2-Mechanics/NPCs/Harbin Wester.md|Harbin Wester]]"
questLocationObtained: questBoard
questSessionObtained: 
questNotes: 
questLootAvail: 
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

# `=this.file.name`

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(Ready for party), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

 "A clan of reclusive rock gnomes resides in a small network of caves in the mountains to the southeast. The gnomes of Gnomengarde are known for their magical inventions, and they might have something with which to defeat the dragon. Get whatever you can from them. If you bring back something useful and don't want to keep it for yourselves, Townmaster Harbin Wester will pay you 50 gp for it." 
 
 If the characters undertake this quest, proceed with "[[08-gnomengarde|Gnomengarde]]."

### Quest Objective

- [[08-gnomengarde|Gnomengarde]]
To complete the Gnomengarde Quest, the characters must obtain at least one magic item from the gnomes. Of the items they can secure, only the [hat of wizardry](app://obsidian.md/2-Mechanics/CLI/items/hat-of-wizardry-xge.md) interests Townmaster Harbin Wester, who offers to buy it for 50 gp even though he knows no one who can attune to it. However, the gnomes won't hand over any magic items until the characters speak to Fibblestib and Dabbledob in area G11.

G3/5/8 signs of struggle
G4/9/12 shares info about the kings madness, DC 18 CHA/intimidation
G7 mimic madness, dc 12 cha
G10 Danger! lever AC 15
G11 borrowed spellbook, DC 15 CHA
G11 Magic items: [[hat-of-wizardry-xge|Hat of Wizardry]], [[wand-of-pyrotechnics-xge]], [[clockwork-amulet-xge|Clockwork Amulet]], [[pole-of-collapsing-xge|Pole of Collapsing]]

G4
- Joybell (female) uses a poker to stoke the fire of a hot iron stove standing against the east wall.
- Dimble (male) uses a complicated press-like contraption to squeeze oil out of a big red mushroom and filter the liquid into four oil flasks.
- Panana (female) stands atop a low table and uses a mechanical rolling pin contraption to kneed green bread dough. The severed caps of several big green mushrooms are set around her.
- Uppendown (male) forms the dough into loaves of green bread, his tongue sticking out as he carefully shapes each loaf like a master sculptor.
- Tervaround (female) teeters on a stool as she stuffs a big purple mushroom into a barrel, so that it can ferment and be turned into mushroom wine.

G7
* Facktoré

G9
* Ulla
* Pog

G11
- Fibblestib 
- Dabbledob

G12
* Caramip
* Jabby
* Nyx
* Quippy (females)
* Anverth
* Delebean
* Pallabar
* Zook (males)

G15
* King Korboz
* King Gnerkli

### Rewards

- 50 [[gold-gp]]
