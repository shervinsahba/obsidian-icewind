---
dg-publish: true
role: Servant at Caer Dineval
age: Teenage
race: Tiefling
gender: Woman
descriptors: ["Frightened","Naive","Helper"]
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
