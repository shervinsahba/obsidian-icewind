---
dg-publish: true
role: Dwarven Valley miner
race: Dwarf
---

> [!info]+
> ## Dwarven Valley miner

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
