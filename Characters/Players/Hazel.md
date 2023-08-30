---
dg-publish: true
role: Monk, Way of the Sun Soul
age: Young Adult
race: Halfling
gender: Woman
descriptors: [""]
---

> [!info]+
> **`=this.role`**
> Background: Folk Hero
>![[pc - Hazel.png]]

![[advancement_monk.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0]) 
SORT file.name DESC
```



