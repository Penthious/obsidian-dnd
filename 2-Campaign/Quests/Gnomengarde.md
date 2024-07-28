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

### Rewards

- 50 [[gold-gp]]
