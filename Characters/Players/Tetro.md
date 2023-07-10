---
dg-publish: true
role: Druid, Circle of the Stars
race: Tortle
---

> [!info]+
> ## Tetro
> ## Druid, Circle of the Stars
> ### Background: Remote Stargazer
>![[pc - Tetro.png]]

![[advancement_druid.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



