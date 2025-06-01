---
dg-publish: true
role: Head Hag of the Cauldron Caves
age: Unknown
race: Hag
gender: Woman
descriptors: Tricksy, Terrible, Powerful]
status: DEAD
---


> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
