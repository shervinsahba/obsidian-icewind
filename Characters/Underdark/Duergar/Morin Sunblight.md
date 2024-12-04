---
dg-publish: true
role: Duergar, Child of Xardorok
age: Adult
race: Duergar
gender: Unknown
descriptors: [Serious, Trained, Prideful]
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