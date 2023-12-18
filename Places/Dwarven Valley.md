---
dg-publish: True
---
![[map-DwarvenValley.png]]
# Characters
```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Dwarven Valley"
SORT file.name
```

# Locations 
The Dwarven Valley was a deep rift in Icewind Dale, located along the southern slopes of the mountain called [[Kelvin's Cairn]]. Within the valley was a complex network of tunnels, subterranean passages and mines that composed the home of the dale's dwarves, particularly those from Clan Battlehammer.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
![[heraldry - Clan Battlehammer.png]]

