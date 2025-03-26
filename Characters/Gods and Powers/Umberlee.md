---
dg-publish: true
role: Goddess of the Sea
age: Ageless
race: God
gender: Woman
descriptors: [Malicious, Capricious, Turbulent]
---

> [!info]+
> **`=this.role`**
> The Wave Mother. The Bitch Queen.
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
