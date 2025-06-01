---
dg-publish: true
role: God of Storms
age: Ageless
race: God
gender: Man
descriptors: [Destructive, Vengeful, Impulsive]
status:
---

> [!info]+
> **`=this.role`**
> The Storm Lord. The Wildfire.
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
