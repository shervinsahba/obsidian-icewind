---
dg-publish: true
role: Speaker of Targos
race: 
---

> [!info]+
> ## Speaker of Targos
>![[npc_Speaker_Naerth_Maxildanar_2.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```

