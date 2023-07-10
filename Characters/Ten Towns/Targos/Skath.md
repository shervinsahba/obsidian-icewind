---
dg-publish: true
role: Targos Militia Captain
race: Tiefling
---

> [!info]+
> ## Targos Militia Captain
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
