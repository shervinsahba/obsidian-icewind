---
dg-publish: true
role: Enlightened Penguin
age: Youth
race: Penguin
gender: Male
descriptors: [Chill, Gullible, Ride or Die]
status:
aliases:
  - 
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
