---
dg-publish: true
role: Lieutenant of Revel's End
age: Adult
race: Half-Orc
gender: Woman
descriptors: [Dutiful, Patient, Lawful]
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

