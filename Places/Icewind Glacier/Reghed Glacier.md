---
dg-publish: True
---

> [!info]+
> The Reghed Glacier was a glacial wasteland north of the Spine of the World. The region was so desolate and isolated that few travelers dared to cross near its eastern border, let alone venture atop its icy facade. The Reghed barbarians of Icewind Dale took their name from this glacier.
> ![[reghed_glacier.png]]

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```