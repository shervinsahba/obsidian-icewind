---
dg-publish: true
role: Hunter from Lonelywood
age: Old
race: Human
gender: Man
descriptors: [Woodsman, Heartbroken, Alcoholic]
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
