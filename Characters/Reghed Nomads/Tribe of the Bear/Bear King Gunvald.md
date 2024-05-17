---
dg-publish: true
role: Bear Tribe King
age: Middle-aged
race: Human
gender: Man
descriptors: Powerful, Grizzly, Hulk
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
