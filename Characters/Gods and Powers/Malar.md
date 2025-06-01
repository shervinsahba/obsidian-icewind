---
dg-publish: true
role: God of Beasts
age: Ageless
race: God
gender: Man
descriptors: [Bestial, Predatory, Graceful]
status:
---

> [!info]+
> **`=this.role`**
> The Beast Lord. Master of the Hunt.
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
