---
dg-publish: true
role: Mage
age: Young Adult
race: Tiefling
gender: Woman
descriptors: ["Quiet", "Angsty", "Mysterious", DEAD]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[npc_Astrix.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```