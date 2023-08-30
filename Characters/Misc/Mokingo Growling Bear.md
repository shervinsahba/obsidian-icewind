---
dg-publish: true
role: Adventurer, Clan of the Bear
age: Adult
race: Goliath
gender: Man
descriptors: [Dead, Ferocious, Wanderer]
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