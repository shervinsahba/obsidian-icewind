---
dg-publish: true
role: Former Wolf Tribe, Midwinter Child
age: Young
race: Human
gender: Man
descriptors: [Survivor, Traumatized, Innocent]
status: 
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
