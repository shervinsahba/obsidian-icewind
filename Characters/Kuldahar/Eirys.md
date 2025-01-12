---
dg-publish: true
role: Counsel Member of Kuldahar
age: Adult
race: Aasimar
gender: Woman
descriptors: ["Intense","Gallant","Goal-Oriented"]
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
