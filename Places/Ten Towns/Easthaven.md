---
dg-publish: true
---
![[heraldry - Easthaven.png|300]]
![[map-Easthaven.jpg|1000]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "Characters/Ten Towns/Easthaven"
SORT file.name
```

# Locations
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
