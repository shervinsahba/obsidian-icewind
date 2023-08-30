---
dg-publish: true
role: Innkeeper of the Eastside
age: Teenage
race: Human
gender: Woman
descriptors: [Caring, Tired, Singer]
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

