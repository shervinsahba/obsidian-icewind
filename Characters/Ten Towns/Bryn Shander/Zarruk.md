---
dg-publish: true
role: Zhentarim tavern keeper at the Hooked Knucklehead
race: Half-orc
---

> [!info]+
> ## Tavern keeper at the Hooked Knucklehead
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
