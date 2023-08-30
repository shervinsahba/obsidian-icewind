---
dg-publish: true
role: Druid, Circle of the Stars
age: Adult
race: Tortle
gender: Man
descriptors: [""]
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
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



