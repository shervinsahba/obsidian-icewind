---
dg-publish: true
role: Dwarven Valley miner
age: Old
race: Dwarf
gender: Man
descriptors: [Gruff, Silent, Frostbitten]
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
