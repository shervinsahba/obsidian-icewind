---
dg-publish: true
role: Speaker of Caer Konig
age: Adult
race: Dragonborn
gender: Man
descriptors: ["Chatty","Heroic","Drunkard"]
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
