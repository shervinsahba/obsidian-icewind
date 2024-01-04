---
dg-publish: true
role: Speaker of Easthaven
age: Adult
race: Human
gender: Man
descriptors: [Experienced, Tired, Pragmatic]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[speaker_danneth_waylen.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

