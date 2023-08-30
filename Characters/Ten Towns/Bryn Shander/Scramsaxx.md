---
dg-publish: true
role: Tavernkeeper of the Northlook, former Sellsword
age: Adult
race: Human
gender: Woman
descriptors: [Sly, Friendly, Tough]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`

> *Grab a seat and warm your bottoms! Mead or firewater? We sling it sweeter and cheaper than Ogden's!* 

> *Ah, one rule. Don't touch [[Ol Bitey]].*

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```


