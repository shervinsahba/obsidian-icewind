---
dg-publish: true
role: Acolyte of Lathander
age: Unknown-Aged
race: Gnome
gender: Man
descriptors: [Curmudgeon, Intelligent, Furry]
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
