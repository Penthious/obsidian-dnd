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

The local midwife -- an acolyte of Chauntea named [[Adabra Gwynn]]-- lives by herself in a stone windmill on the side of a hill a few miles south of Phandalin. With dragon sightings becoming common, it's not safe for her to be alone. Urge [[Adabra Gwynn]] to return to Phandalin. Once she's safe, visit Townmaster [[Harbin Wester]] to claim a reward of 25gp

### Quest Objective

- [[14-umbrage-hill|Umbrage Hill]]

### Rewards

- 25 [[gold-gp]]
- Also 1 [[potion-of-healing]] from [[Adabra Gwynn]] when party rescues her