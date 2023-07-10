---
dg-publish: true
role: Tavernkeeper
race: Human
---

> [!info]+
> ## Tavernkeeper of the Lucky Liar
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
