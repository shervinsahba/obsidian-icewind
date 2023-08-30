---
dg-publish: true
role: Veteran Bounty Hunter
age: Mature
race: Dwarf
gender: Woman
descriptors: [Sharp, Righteous, Straightshooter]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Hlin Trollbane.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```