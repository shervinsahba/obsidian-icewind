---
dg-publish: true
role: Auril's Mount
age: Unknown-Aged
race: Roc
gender: Unknown-Gender
descriptors: [Primal, Predatory, Bird]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[npc_auril_and_iskra.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
