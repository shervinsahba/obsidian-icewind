---
dg-publish: true
role: Speaker of Bremen
age: Elderly
race: Dwarf
gender: Man
descriptors: ["Possibly Senile"]
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
