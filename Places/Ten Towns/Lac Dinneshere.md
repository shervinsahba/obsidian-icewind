---
dg-publish: True
---
> [!info]+
The lake around which Western Ten Towns has been settled. [[Easthaven]], [[Caer Dineval]], and [[Caer Konig]] are all along the lake. In warmer times, a ferry transports men and goods for a modest fee between the three towns.
![[lac_dinneshere.png]]

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
