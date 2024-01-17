---
dg-publish: true
role: Mountaineer at Frozenfar Expeditions
age: Adult
race: Dwarf
gender: Man
descriptors: [Boisterous, Brave, Ranger]
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

