---
dg-publish: True
---
![[map-ElvenTomb.png]]
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

![[elven_tomb.png]]