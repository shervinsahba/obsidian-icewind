---
dg-publish: true
---
![[heraldry - Caer Dineval.png|300]]
![[map-Caer-Dineval.jpg|600]]
![[caer-dineval.png]]
# Characters
```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Caer Dineval"
SORT file.name
```

# Locations
## Dinev's Rest
Abandoned inn in disrepair.
## Uphill Climb
Tavern overlooking Lac Dinneshere, halfway up the hill to the Caer.
## The Caer
The fortified keep around which the town was built.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
