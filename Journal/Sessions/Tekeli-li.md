---
dg-publish: true
role: Chillbringer, Aspect of Isolation
age: Ancient
race: Gnoll
gender: Vampiress
descriptors: [Ravenous, Antagonizing, Hunter]
status: DEAD
aliases:
  - Aspect of Isolation
  - Chosen of Isolation
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
