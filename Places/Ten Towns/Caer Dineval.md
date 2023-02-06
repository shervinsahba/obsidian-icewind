---
dg-publish: true
---
![[map-Caer-Dineval.jpg|800]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "NPCs/Ten Towns/Caer Dineval"
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
![[heraldry - Caer Dineval.png|300]]