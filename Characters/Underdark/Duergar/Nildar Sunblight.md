---
dg-publish: true
role: Duergar Warlord, 5th Son of Xardorok
age: Adult
race: Duergar
gender: Man
descriptors: ["","",""]
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