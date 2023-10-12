---
dg-publish: true
---
![[heraldry - Good Mead.png|300]]
![[map-Good Mead.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Good Mead"
SORT file.name
```

# Locations
## Mead Hall
## Shrine of the Flaming Sword
## Loggers Lodges

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
