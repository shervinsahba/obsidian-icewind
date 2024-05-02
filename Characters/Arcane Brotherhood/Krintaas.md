---
dg-publish: true
role: Dzaan's Bodyguard
age: Unknown-Aged
race: Undead
gender: Man
descriptors: [Stoic, Grim, DEAD]
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