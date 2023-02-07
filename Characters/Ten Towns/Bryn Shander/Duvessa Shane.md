---
dg-publish: true
role: Speaker of Brynn Shander
race: Human
---

> [!info]+
> ## Speaker of Brynn Shander
> ![[npc_Speaker_Duvessa_Shane.png| 300]]

> *You ask why I consort with the Brotherhood? Because these mages bring power, and power alongside unity, is what we Dalefolk need is to survive... And surviving this winter is all I care to see through... Unfortunately, this sentiment is not shared amongst all speakers.*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```