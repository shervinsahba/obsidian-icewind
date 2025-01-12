---
dg-publish: true
role: Keeper of the Heartstone Gem
age: Old
race: Human
gender: Man
descriptors: ["Druidic","Earthy","Oddball"]
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
