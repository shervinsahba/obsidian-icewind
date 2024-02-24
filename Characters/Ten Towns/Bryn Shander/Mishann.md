---
dg-publish: true
role: Priestess of the Morning Lord
age: Adult
race: Human
gender: Woman
descriptors: [Headstrong, Helpful, Ex-Adventurer]
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
