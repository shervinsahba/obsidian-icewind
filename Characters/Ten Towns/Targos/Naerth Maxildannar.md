---
dg-publish: true
role: Speaker of Targos
race: 
---

> [!info]+
> ## Speaker of Targos
> ![[npc_unknown.png| 300]]

> *Beware the Speaker of Targos.* - [[Hlin Trollbane]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```

