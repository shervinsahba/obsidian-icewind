---
dg-publish: true
role: Biologist
age: Young
race: Half-Elven
gender: Person
descriptors: [""]
---

> [!info]+
> ## `=this.role`
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
