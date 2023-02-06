---
dg-publish: true
---

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #battle 
FLATTEN x WHERE contains(x,"battle") 
SORT file.name DESC
```