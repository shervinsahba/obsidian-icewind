---
dg-publish: true
role: Mage Researcher at Kuldahar
age: Adult
race: Half-orc
gender: Man
descriptors: ["Mysterious","Masked","Aloof"]
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
