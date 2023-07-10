---
dg-publish: true
role: Arcane Brotherhood Mage
race: Human
---

> [!info]+ 
> ## Arcane Brotherhood Mage
> ![[npc_vellyne.png.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

