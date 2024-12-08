---
dg-publish: true
role: Dwarven Valley Clan Leader
age: Adult
race: Dwarf
gender: Man
descriptors: [Honorbound, Ambitious, Tough]
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
