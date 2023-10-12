---
dg-publish: true
role: Deceased Speaker of Good Mead
age: Adult
race: Human
gender: Man
descriptors: [Stalwart, Hot-Headed, Dead]
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
