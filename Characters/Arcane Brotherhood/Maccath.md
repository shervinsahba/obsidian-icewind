---
dg-publish: true
role: Former Arcane Brotherhood Member
age: Unknown-Aged
race: Human
gender: Man
descriptors: [Pseudonym used by Macreadus to access Brotherhood networks]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> See [[Macreadus]].


```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```