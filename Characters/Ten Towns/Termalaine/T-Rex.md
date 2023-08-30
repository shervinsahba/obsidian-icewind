---
dg-publish: true
role: Kobold Kommander
age: Adult
race: Kobold
gender: Man
descriptors: [Boss, Total dragon, Badass wings]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_trex.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
