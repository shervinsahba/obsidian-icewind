---
dg-publish: true
role: Tavernkeeper of Kelvin's Comfort
race: Dwarf
---

> [!info]+
> ## Tavernkeeper of Kelvin's Comfort
> ![[npc_Ogden_Flamebeard.png| 300]]

> *Flamebeard's Firewater! I distill it meself. The good stuff right there!*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```