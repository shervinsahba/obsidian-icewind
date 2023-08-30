---
dg-publish: true
role: Scholar
age: Middle-Aged
race: Half-Elf
gender: Woman
descriptors: [Scattered, Bookworm, Inquisitive]
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
