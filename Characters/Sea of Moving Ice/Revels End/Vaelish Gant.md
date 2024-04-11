---
dg-publish: true
role: Prisoner 237 and Disgraced Brotherhood Wizard
age: Adult
race: Human
gender: Man
descriptors: [Pompous, Conniving, Smarmy]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[vaelish_gant.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

