---
dg-publish: true
role: Adventurer hired by Dzaan
age: Adult
race: Dwarf
gender: Unknown
descriptors: []
status: DEAD
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```