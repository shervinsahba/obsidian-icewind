---
dg-publish: true
role: Zhentarim, Tavernkeeper of the Hooked Knucklehead
age: Adult
race: Half-Orc
gender: Man
descriptors: [Brutish, Coin-driven, Lout]
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
