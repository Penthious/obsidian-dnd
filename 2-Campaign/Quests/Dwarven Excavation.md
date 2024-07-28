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

"Dwarf prospectors found ancient dwarven ruins in the mountains southwest of here, and have been working an archaeological dig seeking treasure and relics. They need to be warned that a white dragon has moved into the area. Take the warning to them, then return to Townmaster Harbin Wester to collect a reward of 50 gp." If the characters undertake this quest, see "Dwarven Excavation."

### Quest Objective

- [[06-dwarven-excavation|Dwarven Excavation]]

### Rewards

- 50 [[gold-gp]]
