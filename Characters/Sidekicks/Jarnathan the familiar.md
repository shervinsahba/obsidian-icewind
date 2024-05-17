---
dg-publish: true
role: Fern's Familiar
age: Ageless
race: Familiar
gender: Being
descriptors: [""]
---

> [!info]+
> **`=this.role`**

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```



