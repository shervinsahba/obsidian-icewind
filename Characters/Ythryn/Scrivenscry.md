---
dg-publish: true
role: Arcanaloth
age: Unknown
race: Yugoloth
gender: Unknown
descriptors: [Mendacious, Disloyal, Covetous]
status: GONE
aliases:
  - 
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
