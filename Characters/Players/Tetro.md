---
dg-publish: true
role: Druid, Circle of the Stars
age: Adult
race: Tortle
gender: Man
descriptors: [Adventurer]
status: 
---

> [!info]+
> **`=this.role`**
> Background: Remote Stargazer
>![[pc - Tetro.png]]

![[advancement_druid.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```



