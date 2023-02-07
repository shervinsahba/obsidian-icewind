---
dg-publish: true
role: Singing Fish
race: Knucklehead Trout
---

> [!info]+
> ## Singing fish
> ![[ol-bitey.png| 300]]

> *There's a place I like to go*
> *Farther up the river's flow*
> *Where it is, I do not know*
> *Must be under all that snow*

> *A knucklehead trout enchanted to sing by a knucklehead lout* - Scramsaxx.

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```