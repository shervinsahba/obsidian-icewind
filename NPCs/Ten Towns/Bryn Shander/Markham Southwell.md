---
dg-publish: true
role: Sheriff of Brynn Shander
race: Human
---

> [!info]+
> ## Sheriff of Bryn Shander
> ![[npc_Sheriff_Markham_Southwell.png| 300]]

> *I've had it with these monkey fighting yetis on this Monday to Friday plain.*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```