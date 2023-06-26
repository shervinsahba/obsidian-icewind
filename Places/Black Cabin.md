---
dg-publish: True
---
![[Black-Cabin-still.png| 600]]
![[2-22 Black Cabin.jpg| 600]]
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```