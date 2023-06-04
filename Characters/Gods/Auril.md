---
dg-publish: true
role: Goddess of Winter
race: God
---

> [!info]+
> ## Auril, Goddess of Winter.
> ### The Frostmaiden. Lady Icekiss.
> ![[auril_spark.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
