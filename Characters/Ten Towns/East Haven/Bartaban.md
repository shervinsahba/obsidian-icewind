---
dg-publish: true
role: Innkeeper of the White Lady
age: Adult
race: Human
gender: Man
descriptors: [Jaded, Normal, Commoner]
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

