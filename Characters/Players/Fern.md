---
dg-publish: true
role: Rogue, Arcane Trickster
age: Middle-Aged
race: Tiefling
gender: Woman
descriptors: []
---

> [!info]+
> **`=this.role`**
> Background: Penetration Tester
> ![[pc - Fern.png]]

![[advancement_rogue.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```


![[pc - Fern by Meg.png]]