---
dg-publish: true
role: Arcane Brotherhood Wizard
age: Unknown-Aged
race: Human
gender: Man
descriptors: [Ambitious, Erudite, Cunning, DEAD]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
![[dzaan.png|300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```