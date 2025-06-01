---
dg-publish: true
role: Archdevil, Lord of Nessus, Overlord of the Nine Hells
age: Ancient
race: Fiend
gender: Male
descriptors: [Articulate, Certain, Fearsome]
status:
---

> [!info]+
> **`=this.role`**
>  Lord of the Nine, The Cloven
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

![[asmodeus.png]]

> The archdevil Asmodeus is the ultimate ruler of the [[Nine Hells]]. He rules from Nessus, the deepest layer. He is worshiped as a deity in many worlds, while in others he is believed to be a being more ancient than the deities themselves. 


```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
