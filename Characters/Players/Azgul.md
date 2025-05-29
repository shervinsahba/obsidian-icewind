---
dg-publish: true
role: Warlock, Pact of the Hexblade
age: Adult
race: Half-orc
gender: Man
descriptors: []
status:
---

> [!info]+
> **`=this.role`**
> Background: Sage
>![[pc - Azgul.png]]

![[advancement_warlock.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```



