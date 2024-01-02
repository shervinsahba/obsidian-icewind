---
dg-publish: true
role: Notary Scribe, Imprisoned at Caer Dineval
age: Middle-Aged
race: Human
gender: Man
descriptors: ["Feisty","Spry",""]
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
