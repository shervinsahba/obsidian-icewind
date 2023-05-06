---
dg-publish: true
role: Adventurer, Clan of the Bear Tribesman
race: Goliath
---

> [!info]+
> ## Clan of the Bear Tribesman
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
