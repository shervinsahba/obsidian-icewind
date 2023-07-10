---
dg-publish: true
role: Dwarven Valley miner
race: Dwarf
---

> [!info]+
> ## Dwarven Valley miner, brother of [[Oobok]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
