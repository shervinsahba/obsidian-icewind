---
dg-publish: true
role: Clerk at Easthaven Town Hall
age: Young Adult
race: Human
gender: Woman
descriptors: [Squirrelly, Fastidious, Secratarial]
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

