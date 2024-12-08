---
dg-publish: true
---

Located in the heart of [[Bryn Shander]], the Hooked Knucklehead tavern has become a base and bastion for the [[Heroes of the Cairn]].

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
