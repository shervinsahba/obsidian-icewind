---
dg-publish: true
role: Missing Innkeeper's Son at Buried Treasures
age: Young
race: Human
gender: Man
descriptors: ["Heroic","Recently change in demeanor","Missing"]
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
