---
dg-publish: true
role: Merchant Caravaner
age: Middle-Aged
race: Dwarf
gender: Man
descriptors: [Unscrupulous, Capistalistic, Shrewd]
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