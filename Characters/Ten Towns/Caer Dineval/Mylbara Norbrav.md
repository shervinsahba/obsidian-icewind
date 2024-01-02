---
dg-publish: true
role: Translator, Imprisoned at Caer Dineval
age: Middle-Aged
race: Dwarf
gender: Woman
descriptors: ["Educated","Stout","Hard-headed"]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
