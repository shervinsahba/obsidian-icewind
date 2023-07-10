---
dg-publish: true
role: Veteran Bountyhuntress
race: Dwarf
---

> [!info]+
> ## Veteran Bountyhuntress
> ![[npc_Hlin Trollbane.png| 300]]

> *The murders started in Easthaven, moved to Bryn, and now Targos. I know it's a hunch, but I can't shake it... They're linked I tell ya. Dalefolk, as gruff as we are, are too busy surviving to cut each other down.*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```