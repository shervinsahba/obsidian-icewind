---
dg-publish: false
role: 
race: 
---

> [!info]+
> ## 
> ![[npc_unknown.png | 300]]
> - 

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
