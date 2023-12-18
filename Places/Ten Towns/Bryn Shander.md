---
dg-publish: true
---
![[heraldry - Bryn Shander.png| 300]]
![[map-BrynShander-updatedwithStormKing.png| 1000]]

# Characters
```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Bryn Shander"
SORT file.name
```

# Locations 
## Market Square
## Blackiron Blades
Local smith. Not the finest craftsmanship, but they'll do in a pinch.
## Kadu's Wonderous Scrolls
A mysterious magic shop, not initially open when the party first visited.
## Stables
## Council Hall
## Speaker's Palace
## Armory
Armory used by the militia. Sheriff is [[Markham Southwell]].
## The Hooked Knucklehead
[[Lore/Peoples/Zhentarim]] managed tavern.
## The Northlook
A well-frequented tavern. Tavern keeper [[Scramsaxx]] seems to know much local gossip. [[Ol Bitey]] lives on the wall.
## Kelvin's Comfort 
A comfortable inn and small tavern, whose keeper [[Ogden Flamebeard]] keeps busy due to his firewater whiskey.
## House of the Morninglord
Temple of [Lathander](https://forgottenrealms.fandom.com/wiki/Lathander) and shrine to [Amauntor](https://forgottenrealms.fandom.com/wiki/Amaunator), deities and aspects of the Sun, Spring, and Order.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
