---
dg-publish: true
role: Wyrmdoom Tribe Member
age: Adult
race: Goliath
gender: Male
descriptors: [Honorable, Dull-witted, Angry]
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
