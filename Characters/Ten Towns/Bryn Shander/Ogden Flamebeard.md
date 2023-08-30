---
dg-publish: true
role: Tavernkeeper of Kelvin's Comfort
age: Middle-Aged
race: Dwarf
gender: Man
descriptors: [Proud, Hot-Headed, Good-Hearted]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Ogden_Flamebeard.png| 300]]

> *Flamebeard's Firewater! I distill it meself. The good stuff right there!*

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```