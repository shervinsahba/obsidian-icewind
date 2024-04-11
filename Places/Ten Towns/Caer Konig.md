---
dg-publish: true
---
![[heraldry - Caer Konig.png|300]]
![[map-Caer-Konig.jpg|600]]
# Characters
```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Caer Konig"
SORT file.name
```

# Locations
## Frozenfar Expeditions
## The Hook, Line, and Sinker
## The Northern Light

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
