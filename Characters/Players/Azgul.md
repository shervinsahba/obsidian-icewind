---
dg-publish: true
role: Warlock, Pact of the Hexblade
age: Adult
race: Half-orc
gender: Man
descriptors: [""]
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
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



