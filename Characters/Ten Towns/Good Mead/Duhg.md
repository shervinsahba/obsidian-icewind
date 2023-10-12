---
dg-publish: true
role: Verbeeg
age: Adult
race: Giant
gender: Man
descriptors: [Survivalist, Raider, Outcast]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[verbeeg.png|300]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
