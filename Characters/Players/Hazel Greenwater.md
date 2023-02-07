---
dg-publish: true
role: Monk
race: Halfling
---

> [!info]+
> ## Monk
> ### Background: Folk Hero
>![[pc - Hazel.png]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0]) 
SORT file.name DESC
```



