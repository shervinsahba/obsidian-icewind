---
dg-publish: true
role: Garrett's good boy
age: "Adult"
race: Dog
gender: "Male" 
descriptors: [Loyal, Alert, Clever]
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
