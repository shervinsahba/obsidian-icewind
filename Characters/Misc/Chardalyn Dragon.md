---
dg-publish: true
role: Siege Weapon
age: Adult
race: Dragon
gender: Construct
descriptors: ["Robotic", "Evil", "Powerful"]
status: DEAD
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