---
dg-publish: true
role: Tavernkeep of the Lucky Liar
age: Adult
race: Human
gender: Woman
descriptors: [All-knowing, Shady, Vigilant]
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
