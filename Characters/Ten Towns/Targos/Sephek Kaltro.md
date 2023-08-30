---
dg-publish: true
role: Mercenary working for Torg, Former Sailor
age: Adult
race: Human
gender: Man
descriptors: [Well-spoken, Cold-Hearted, Ruthless]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[rotf_23_sephek_kaltro.png]]


```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
