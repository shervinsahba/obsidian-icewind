---
dg-publish: true
role: Shopkeeper of The Happy Scrimshander, Former Assassin
age: Middle-Aged
race: Human
gender: Woman
descriptors: [Doughy, Spinster, Nostalgic]
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
