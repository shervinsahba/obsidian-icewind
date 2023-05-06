---
dg-publish: true
role: Kobold Kommander
race: Kobold
---

> [!info]+
> ## Kobold Kommander
> ![[npc_trex.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
