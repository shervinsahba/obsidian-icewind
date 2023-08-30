---
dg-publish: true
role: Innkeeper at the Luskan Arms
age: Middle-Aged
race: Human
gender: Man
descriptors: [Depressed, Dispassionate, Lackey]
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
