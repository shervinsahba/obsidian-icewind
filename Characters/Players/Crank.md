---
dg-publish: true
role: Monk, Way of the Drunken Master
race: Bugbear
---

> [!info]+
> **`=this.role`**
> Background: Criminal
> ![[pc - Crank.png]]

![[advancement_monk.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



