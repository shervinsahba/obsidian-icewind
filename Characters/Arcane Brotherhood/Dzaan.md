---
dg-publish: true
role: Arcane Brotherhood Member
race: 
---

> [!info]+ 
> ## Arcane Brotherhood Member
> ![[npc_unknown.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```