---
dg-publish: true
role: Barbarian
race: Half-orc
---

> [!info]+
> ## Barbarian
> ### Background: Outlander
>![[pc - Oona.png]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```



