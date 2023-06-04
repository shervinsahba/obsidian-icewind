---
dg-publish: true
role: Shopkeeper of The Happy Scrimshander, Former Assassin
race: Half-elf
---

> [!info]+
> ## Shopkeeper of The Happy Scrimshander, Former Assassin
> ![[npc_unknown.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
