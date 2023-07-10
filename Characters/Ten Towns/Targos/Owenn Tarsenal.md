---
dg-publish: true
role: Innkeeper at the Luskan Arms
race: Human
---

> [!info]+
> ## Innkeeper at the Luskan Arms
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
