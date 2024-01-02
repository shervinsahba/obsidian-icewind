---
dg-publish: true
role: Gate Guard, Black Swords Cultist
age: Adult
race: Tiefling
gender: Woman
descriptors: ["Disingenuous","Fervent","Cultist"]
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
