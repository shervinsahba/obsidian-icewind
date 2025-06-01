---
dg-publish: true
role: Professor Orb
age: Unknown
race: Item
gender: Man
descriptors: [Pompous, Well-read, Condescending]
status: ITEM
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
