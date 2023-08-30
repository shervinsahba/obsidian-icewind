---
dg-publish: true
role: Speaker of Termalaine
age: Adult
race: Half-Orc
gender: Man
descriptors: ["Good-hearted, Boisterous"]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Speaker_Oarus_Masthew.png| 300]]


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
