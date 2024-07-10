---
questObtained: 
questStatus: In Progress
questGiver: "[[2-Mechanics/CLI/bestiary/npc/gundren-rockseeker-pabtso.md|gundren-rockseeker-pabtso]]"
questLocationObtained: 
questSessionObtained: "[[1-Session Journals/2024-06-01.md|2024-06-01]]"
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
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

Describe the quest here. 

### Quest Objective

- List the objectives here.

### Rewards

- List the rewards here.
