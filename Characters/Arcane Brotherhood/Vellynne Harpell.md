---
dg-publish: true
role: Arcane Brotherhood Wizard
age: Old
race: Human
gender: Woman
descriptors: [Pragmatic, Astute, Wealthy]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[vellynne.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

