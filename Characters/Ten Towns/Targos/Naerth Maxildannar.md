---
dg-publish: true
role: Speaker of Targos
age: Middle-Aged
race: Human
gender: Man
descriptors: [Slimy, Conniving, Sly]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
>![[npc_Speaker_Naerth_Maxildanar_2.png| 300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```

