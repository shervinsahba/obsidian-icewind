---
dg-publish: true
role: Monk, Way of the Drunken Master
age: adult
race: Bugbear
gender: Man
descriptors: [Adventurer]
status: 
---

> [!info]+
> **`=this.role`**
> Background: Criminal
> ![[pc - Crank.png]]

![[advancement_monk.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
```



