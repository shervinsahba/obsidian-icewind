---
dg-publish: true
role: Frost Druid
race: Halfling
---

> [!info]+
> ## Frost Druid
> ![[npc_ravisin.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
