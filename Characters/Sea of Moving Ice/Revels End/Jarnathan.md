---
dg-publish: true
role: Absolution Council Member as Revel's End
age: Adult
race: Aarakocra
gender: Man
descriptors: [Bird, Best, Unpunctual]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

