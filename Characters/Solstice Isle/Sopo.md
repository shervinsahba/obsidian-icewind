---
dg-publish: true
role: Ice Mephit and Not an Imp
age: Ancient
race: Devil
gender: Male
descriptors: [Chummy,Trollish,Guide]
status:
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```