---
dg-publish: true
---
![[heraldry - Targos.png| 300]]
![[map-Targos.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "Characters/Ten Towns/Targos"
SORT file.name
```

# Locations
## Luskan Arms
Large, central tavern. An old inn run by [[Owenn Tarsenal]]. [[Zhentarim]] drop-off point for stolen goods.
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
