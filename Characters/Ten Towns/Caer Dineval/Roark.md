---
dg-publish: true
role: Tavernkeeper at the Uphill Climb
age: Middle-aged
race: Human
gender: Man
descriptors: ["Good-meaning","Curt","Wary"]
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
