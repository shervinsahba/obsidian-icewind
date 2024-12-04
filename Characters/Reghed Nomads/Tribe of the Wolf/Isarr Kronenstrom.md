---
dg-publish: true
role: Wolf Tribe King
age: Adult
race: Human
gender: Man
descriptors: [Wild, Psychotic, Tenacious]
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
