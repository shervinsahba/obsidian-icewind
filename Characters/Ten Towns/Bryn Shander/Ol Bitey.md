---
dg-publish: true
role: Singing Fish
age: Unknown-Aged
race: "Knucklehead Trout"
gender: Fish
descriptors: [Bitey, Old, Sonorous]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[ol-bitey.png| 300]]

> *There's a place I like to go*
> *Farther up the river's flow*
> *Where it is, I do not know*
> *Must be under all that snow*

> *A knucklehead trout enchanted to sing by a knucklehead lout* - Scramsaxx.

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```