---
dg-publish: true
role: Kennel Boy, Imprisoned at Caer Dineval
age: Young
race: Human
gender: Boy
descriptors: ["Miscreant","Savvy","Coin-minded"]
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
