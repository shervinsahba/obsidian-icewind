---
dg-publish: True
---
![[Black-Cabin-still.png| 600]]
![[Black_Cabin_Ground_SD.png| 600]]
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```