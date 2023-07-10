---
dg-publish: true
role: Auril's Mount
race: Roc
---

> [!info]+
> ## Auril's Roc
> ![[npc_auril_and_iskra.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
