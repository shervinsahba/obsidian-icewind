---
dg-publish: true
role: Arcane Brotherhood Wizard
age: Adult
race: Tiefling
gender: Woman
descriptors: [Haughty, Ambitious, Prodigy]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[avarice_portrait.png|300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

