---
dg-publish: true
role: Dwarven Valley miner
race: Dwarf
note: Torn in half by yeti.
---

> [!info]+
> ## Dwarven Valley miner, brother of [[Oorrok]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
