---
dg-publish: true
---
![[heraldry - Termalaine.png|300]]
![[map-Termalaine.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Termalaine"
SORT file.name
```

# Locations
## The Blue Clam
[[Vernon Braig]]'s harborside tavern, serving chowder and leaded fish cakes. Host tavern to many miners, fishers, and trappers of the area. Frequented by [[Oarus Masthew]].

## The Eastlook
Charming inn, made from a row of connected houses. Run by the willowy teen [[Marta Pekryk]] and her bed-ridden father.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
