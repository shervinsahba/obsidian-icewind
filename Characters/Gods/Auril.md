---
dg-publish: true
role: Goddess of Winter
age: Ageless
race: God
gender: Woman
descriptors: [Isolated, Cruel, Enduring]
---

> [!info]+
> **`=this.role`**
> The Frostmaiden. Lady Icekiss.
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 
> ![[auril_spark.png]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
