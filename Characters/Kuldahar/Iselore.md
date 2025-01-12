---
dg-publish: true
role: Archdruid of Kuldahar
age: Mature
race: Elvish
gender: Woman
descriptors: ["Sagacious","Conservative","Prudent"]
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
