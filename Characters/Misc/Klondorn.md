---
dg-publish: true
role: Duergar Priest in Disguise
age: Ancient
race: Devil
gender: Man
descriptors: [Vile,Masochistic,Sulfurous]
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