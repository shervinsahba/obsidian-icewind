---
dg-publish: true
role: The Winter Walker
age: Unknown-Aged
race: Beast
gender: "Unknown-Gender"
descriptors: [Mysterious, Beastial, Legend]
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