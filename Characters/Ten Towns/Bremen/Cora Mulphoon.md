---
dg-publish: true
role: Innkeeper of Buried Treasures
age: Middle-aged
race: Human
gender: Woman
descriptors: [Anxious, Hospitable, Kind]
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
