---
dg-publish: true
role: Spirit of Lac Dinneshere
age: Unknown
race: Undead
gender: Woman
descriptors: [Grudge, Ringu, Ghastly]
---

It was said that the White Lady was once a mortal woman married to a notoriously stingy man that perished in the waters of [[Lac Dinneshere]]. Both her husband and all his accumulated wealth sunk to the bottom of the Lac Dinneshere when his boat capsized upon its waters.

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[white_lady.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

