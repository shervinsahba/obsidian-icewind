---
dg-publish: true
role: Tavern Keeper at Hook, Line, and Sinker
age: Adult
race: Half-elf
gender: Man
descriptors: [Jovial, Witty, Mercantile]
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

