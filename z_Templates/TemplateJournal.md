---
NoteIcon: journal
aat-render-enabled: true
fc-category:
  - Event Category 1
fc-display-name: 
sessionstatus:
  - Occured
type: Session Journal
sessionDate: 2000-01-01
players: 6
Status:
  - ⏳
OneLiner: 1 Line Summary
timelines:
  - journal
tags:
  - journal
---

<% await tp.file.move("/1-Session Journals/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewJournal");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Date (yyyy-mm-dd)");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

# Roster 

- [[Mighty Meg]] 
- [[Portland]]
- [[Sarkhaan Alegruuth|Sarkhaan]]
- [[Theodore Burgundy|Theodore]]
- [[Valeria]]
- [[Rebecca]]

## Absent


# Session Overview

