---
dg-publish: true
role: Background unknown, a mage.
race: Tiefling
---

> [!info]+
> ## Mage, background unknown
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
