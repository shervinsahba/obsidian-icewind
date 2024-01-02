---
dg-publish: true
role: Dogkeeper, Imprisoned at Caer Dineval
age: Adult
race: Human
gender: Man
descriptors: ["Shy","Kind","Vegan"]
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
