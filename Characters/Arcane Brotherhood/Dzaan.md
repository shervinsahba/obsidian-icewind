---
dg-publish: true
role: Arcane Brotherhood Wizard
age: Unknown-Aged
race: Human
gender: Man
descriptors: [""]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_unknown.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```