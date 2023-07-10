---
dg-publish: true
role: Innkeeper of the Eastlook
race: Human
---

> [!info]+
> ## Innkeeper of the Eastlook
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```