---
dg-publish: true
role: Arcane Brotherhood Contact
race: Human
---

> [!info]+
> ## Arcane Brotherhood Contact
> 

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```