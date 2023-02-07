---
dg-publish: true
role: Tavernkeeper of The Northlook
race: Human
---

> [!info]+
> ## Tavernkeeper of The Northlook, retired sellsword.
> 
> - A well of information about the comings and goings of travelers in [[Bryn Shander]].

> *Grab a seat and warm your bottoms! Mead or firewater? We sling it sweeter and cheaper than Ogden's!* 

> *Ah, one rule. Don't touch [[Ol Bitey]].*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```


