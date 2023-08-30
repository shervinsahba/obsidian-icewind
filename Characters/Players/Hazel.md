---
dg-publish: true
role: Monk, Way of the Sun Soul
race: Halfling
---

> [!info]+
> **`=this.role`**
> Background: Folk Hero
>![[pc - Hazel.png]]

![[advancement_monk.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0]) 
SORT file.name DESC
```



