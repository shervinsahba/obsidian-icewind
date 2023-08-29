---
dg-publish: true
role: Veteran Bountyhuntress
race: Dwarf
---

> [!info]+
> ## Veteran Bountyhuntress
> ![[npc_Hlin Trollbane.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```