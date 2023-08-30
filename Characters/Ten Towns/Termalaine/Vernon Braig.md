---
dg-publish: true
role: Tavernkeeper of the Blue Clam
age: Adult
race: Half-Orc
gender: Man
descriptors: [Creative, Friendly, Nimble]
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
