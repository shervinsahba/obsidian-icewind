---
dg-publish: true
role: Sheriff of Brynn Shander
age: Adult
race: Human
gender: Man
descriptors: [Lawful, Keen-Eyed, Friendly]
---

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors`
> ![[npc_Sheriff_Markham_Southwell.png| 300]]

> *I've had it with these monkey fighting yetis on this Monday to Friday plain.*

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```