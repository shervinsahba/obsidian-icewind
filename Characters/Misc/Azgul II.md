---
dg-publish: true
role: Warlock, Pact of the Hexblade
age: Adult
race: Half-orc
gender: Man
descriptors: ["Clone"]
status: 
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



