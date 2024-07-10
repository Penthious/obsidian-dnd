```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level, Role
from "1-Party/Phandelver and Below Party"
where contains(Role, "Player") 
where contains(Status, "Active")
```
<br> %% this forces a break line into the note %%
