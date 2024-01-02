---
dg-publish: true
role: Black Swords Cult Leader at Caer Dineval
age: Middle-Aged
race: Tiefling
gender: Man
descriptors: ["Charismatic","Thin-skinned","Visionary"]
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
