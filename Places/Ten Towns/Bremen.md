---
dg-publish: true
---
![[heraldry - Bremen.png|300]]
![[map-Bremen.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "Characters/Ten Towns/Bremen"
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
