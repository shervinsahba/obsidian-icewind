---
dg-publish: true
role: Muzgardt-aligned Duergar
age: Mature
race: Duergar
gender: Man
descriptors: [Loyal, Gruff, Serious]
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