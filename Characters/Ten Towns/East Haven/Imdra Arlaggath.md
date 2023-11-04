---
dg-publish: true
role: Captain of Easthaven's Militia
age: Adult
race: Elvish
gender: Woman
descriptors: [Merciless, Just, Veteran]
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

