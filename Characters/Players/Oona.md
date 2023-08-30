---
dg-publish: true
role: Barbarian, Path of the Ancestral Guardian
age: Adult
race: Half-orc
gender: Woman
descriptors: [""]
---

> [!info]+
> **`=this.role`**
> Background: Outlander
>![[pc - Oona.png]]

![[advancement_barbarian.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```



