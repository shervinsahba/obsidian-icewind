---
dg-publish: true
role: Duergar Innkeeper
age: Mature
race: Duergar
gender: Man
descriptors: [Stubborn, Weary, Reticent]
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