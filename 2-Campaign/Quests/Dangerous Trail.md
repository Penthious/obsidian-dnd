---
questObtained: 
questStatus: Not Started
questGiver: 
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
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

Harbin posts official notices on a board beside the door of the townmaster’s hall. He’s looking for someone to head east on the Triboar Trail, where marauders have attacked several caravans near Wyvern Tor. The most recent victims reported that at least one strange goblin accompanied the marauders, who consist of at least an ogre and some bugbears. Harbin is offering a 100 Gold Award contract to any group that can drive the marauders and any goblin companions away. If the party pursues this quest, see Wyvern Tor in chapter 3.

### Quest Objective

- List the objectives here.

### Rewards

- 100 [[gold-gp]]
