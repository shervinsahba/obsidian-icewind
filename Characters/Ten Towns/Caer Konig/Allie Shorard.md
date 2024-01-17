---
dg-publish: true
role: Innkeeper at the Northern Light
age: Adult
race: Human
gender: Woman
descriptors: [Lithe, Charming, Good-natured]
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

