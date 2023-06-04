---
dg-publish: true
role: Speaker of Lonelywood
race: Halfling
---

> [!info]+
> ## Speaker of Lonelywood
> ![[npc_Speaker_Nimsy_Huddle.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
