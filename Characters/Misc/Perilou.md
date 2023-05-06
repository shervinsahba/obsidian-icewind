---
dg-publish: true
role: Acolyte of Yondolla, Goddess of Protection
race: Hafling
---

> [!info]+
> ## Acolyte of Yondolla, Goddess of Protection
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
