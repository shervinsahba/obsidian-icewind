---
dg-publish: true
---
![[heraldry - Caer Dineval.png|300]]
![[map-Caer-Dineval.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "Characters/Ten Towns/Caer Dineval"
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
