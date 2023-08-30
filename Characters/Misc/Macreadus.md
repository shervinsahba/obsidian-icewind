---
dg-publish: true
role: Hermit sage
age: Unknown-Aged
race: Human
gender: Man
descriptors: [Inventor, Spirit, Petty]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[npc_macreadus.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
