---
dg-publish: true
role: Princess of the Muzgardt Clan
age: Mature
race: Duergar
gender: Woman
descriptors: [Wise, Crafty, Patient]
aliases:
  - Olpha
  - Grandolpha
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