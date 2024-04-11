---
dg-publish: true
---
![[heraldry - Bremen.png|300]]
![[map-Bremen.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Bremen"
SORT file.name
```

# Locations
## Town Hall
## Bremen Docks
## Buried Treasures Inn
A hospitable inn run by [[Cora Mulphoon]] and family.
## Five-Tavern Center
Five taverns stand in a semicircle around a central yard
in the heart of Bremen. As the story goes, five brothers
originally intended to build a tavern together, but each
had assumed he would be the one to run the business.
Since none of the brothers would work for the others,
each built his own tavern, and they all compete for
customers. The taverns are:
- Stones
- Even Keel
- River's Mouth
- Grumpy Moose
- Black-Bearded Brother


# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
