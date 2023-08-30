---
dg-publish: true
role: Tavernkeeper of Three Flags Sailing
age: Middle-Aged
race: Human
gender: Woman
descriptors: [Warm, Maternal, Religious]
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
