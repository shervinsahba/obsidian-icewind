---
dg-publish: True
---
![[map-ElvenTomb.png]]
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

![[elven_tomb.png]]