---
dg-publish: true
role: Elk Tribe Scout
age: Adult
race: Human
gender: Man
descriptors: [Grim, Watchful, Weathered]
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
