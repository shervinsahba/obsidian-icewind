---
dg-publish: true
role: Arcane Brotherhood Member
race: 
---

> [!info]+ 
> ## Arcane Brotherhood Member
> ![[npc_unknown.png| 300]]
> - Commissioned the [[Luskan Deliverers]] to transport a parcel - a small metallic box with nary a hinge nor marking - to their contact [[Ragammel]].

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```