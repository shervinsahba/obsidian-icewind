---
dg-publish: true
role: Monstrosity
age: Ancient
race: Monstrosity
gender: Monster
descriptors: [Destructive, Terror, Godzillian]
status: UNKNOWN
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
