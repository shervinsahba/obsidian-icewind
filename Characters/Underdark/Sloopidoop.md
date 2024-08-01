---
dg-publish: true
role: Society of Brilliance Scholar
age: Adult
race: Sahuagin
gender: Person
descriptors: [Boastful, Inquisitive, Scientific]
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
