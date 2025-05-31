---
dg-publish: true
role: Tiger Tribe Queen
age: Adult
race: Human
gender: Woman
descriptors: [Cruel, Enduring, Isolationist]
---

> [!info]+c
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
