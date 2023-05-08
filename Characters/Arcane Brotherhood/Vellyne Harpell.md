---
dg-publish: true
role: Arcane Brotherhood Mage
race: Human
---

> [!info]+ 
> ## Arcane Brotherhood Mage
> ![[npc_unknown.png| 300]]
> - Had met with [[Duvessa Shane]] regarding the prison [[Revel's End]] in the week prior to the party's arrival in [[Bryn Shandar]].

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

