---
dg-publish: true
role: Arcane Brotherhood Contact
race: Human
---

> [!info]+
> ## Arcane Brotherhood Liaison
> 

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```