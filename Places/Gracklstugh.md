---
dg-publish: True
---
> [!info]+
Gracklstugh, the City of Blades, was a duergar city on the shores of the Darklake in the Northdark.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
