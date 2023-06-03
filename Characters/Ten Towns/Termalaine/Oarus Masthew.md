---
dg-publish: true
role: Speaker of Termalaine
race: Half-orc
---

> [!info]+
> ## Speaker of Termalaine
> ![[npc_Speaker_Oarus_Masthew.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
