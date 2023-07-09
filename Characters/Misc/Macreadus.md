---
dg-publish: true
role: Hermit sage
race: Human
---

> [!info]+
> ## Hermit and sage
![[npc_macreadus.png]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```

