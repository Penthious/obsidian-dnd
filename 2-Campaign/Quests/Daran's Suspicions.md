---
questObtained: 
questStatus: Not Started
questGiver: "[[2-Mechanics/NPCs/Daran Edermath.md|Daran Edermath]]"
questLocationObtained: 
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

Daran is concerned about the Redbrands, and he would like to see a group of heroes teach the ruffians a lesson. He tells the characters that it’s time someone took a stand against their leader, whom the outlaws refer to as “Glasstaff.” He knows the Redbrands hang around the Sleeping Giant tap house, but he can also tell the characters that the Redbrands’ safe house lies under Tresendar Manor, the ruin at the east edge of town.

### Quest Objective

- List the objectives here.

### Rewards

- List the rewards here.
