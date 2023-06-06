---
dg-publish: true
---
![[heraldry - Dougans Hole.png|300]]
![[map-Dougans Hole.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "Characters/Ten Towns/Dougin's Hole"
SORT file.name
```

# Locations
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
