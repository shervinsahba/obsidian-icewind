---
dg-publish: true
role: Temporally Lost Prisoner
age: Unknown
race: Doppelganger
gender: Unknown
descriptors: [Rebellious, Sorrowful, Lobotomized]
status: SEQUESTERED
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
