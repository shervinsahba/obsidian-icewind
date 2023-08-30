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
## Town Hall
## Targos Harbor
## Triglio General Store
Triglio takes its name from one old fisherman chantey:
*“Trig-lee-oh, lads, an’ oist upon the line/Trig-lee-oh,
lads. an’ bring yon fishers in.”* The store’s proprietor
is [[Jestin Hunrae]].
## Luskan Arms
Large, central tavern and old inn run by [[Owenn Tarsenal]]. [[Zhentarim]] drop-off point for stolen goods. The seperate second floor is [[Naerth Maxildannar]]'s residence.
## Three Flags Sailing
Tavern ran by [[Ethen Ma Tarbroul]]. 
## Torg's Warehouse
[[Torg]] Merchant Company's main warehouse. The[[Zhentarim]] seem to fence some goods through here.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
