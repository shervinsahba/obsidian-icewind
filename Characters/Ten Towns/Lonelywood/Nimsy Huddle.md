---
dg-publish: true
role: Speaker of Lonelywood
age: Middle-Aged
race: Halfling
gender: Woman
descriptors: [Cheerful, Maternal, Kooky]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Speaker_Nimsy_Huddle.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
