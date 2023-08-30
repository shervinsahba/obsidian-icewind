---
dg-publish: true
role: Acolyte of Yondolla, Goddess of Protection
age: Adult
race: Halfling
gender: Woman
descriptors: [Loyal, Religious, Brave]
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
