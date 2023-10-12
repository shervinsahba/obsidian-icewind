---
dg-publish: true
role: Logger from Good Mead
age: Middle-aged
race: Dwarf
gender: Man
descriptors: [Gruff, Uncouth, No-nonsense]
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
