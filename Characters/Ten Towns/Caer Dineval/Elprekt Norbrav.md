---
dg-publish: true
role: Butler, Imprisoned at Caer Dineval
age: Adult
race: Half-elf
gender: Man
descriptors: ["Effete","Gangly","Sommelier"]
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
