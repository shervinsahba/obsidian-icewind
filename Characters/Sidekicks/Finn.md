---
dg-publish: true
role: Gadget's Homunculus Servant
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



