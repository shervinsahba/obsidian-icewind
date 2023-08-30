---
dg-publish: true
role: Targos Militia Captain
age: Middle-Aged
race: Tiefling
gender: Man
descriptors: [Vigilant, Reticent]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[npc_Skath.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
