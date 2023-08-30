---
dg-publish: true
role: Speaker of Brynn Shander
age: Adult
race: Human
gender: Woman
descriptors: [Pragmatic, Serious, Uptight]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Speaker_Duvessa_Shane.png| 300]]

> *You ask why I consort with the Brotherhood? Because these mages bring power, and power alongside unity, is what we Dalefolk need is to survive... And surviving this winter is all I care to see through... Unfortunately, this sentiment is not shared amongst all speakers.*

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```