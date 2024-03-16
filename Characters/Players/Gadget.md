---
dg-publish: true
role: Artificer, Armorer
age: Adult
race: Gnome
gender: Woman
descriptors: [""]
---

> [!info]+
> **`=this.role`**
> Background: Inventor

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



