---
dg-publish: true
role: Duergar Lord
age: Adult
race: Duergar
gender: Man
descriptors: [Devout,Overzealous,Despot]
status: DEAD
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