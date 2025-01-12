---
dg-publish: true
---

> [!info]+
Kuldahar was a settlement that sprung up around the gargantuan ancient oak tree, holy to the Church of Silvanus in the northern reaches of the Spine of the World mountains.
![[kuldahar.png]]

# Locations
## Counsel Chambers
## Shrine of the Heartstone Gem

## Statue of Silvanus

## Root Cellar

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```