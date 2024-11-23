---
dg-publish: true
role: Speaker of Dougan's Hole
age: Adult
race: Human
gender: Woman
descriptors: [Gritty, Good-hearted, Survivalist]
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

