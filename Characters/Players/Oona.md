---
dg-publish: true
role: Barbarian, Path of the Ancestral Guardian
race: Half-orc
---

> [!info]+
> **`=this.role`**
> Background: Outlander
>![[pc - Oona.png]]

![[advancement_barbarian.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```



