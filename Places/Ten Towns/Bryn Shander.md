---
dg-publish: true
---
![[map-BrynShander-updatedwithStormKing.png]]

# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "NPCs/Ten Towns/Bryn Shander"
SORT file.name
```

# Locations 

## Market Square
> *The thriving market of Bryn Shander is the focal point of
trade in Icewind Dale. Fishers, crafters, and merchants
from the other towns all converge here. Caravans from
the Sword Coast, dwarves from Ironmaster and Kelvin’s
Cairn, and rarely, hunters from goliath tribes of the
tundra all meet here as well.*
- A carpenter was crafting a bulletin board.

## Blackiron Blades
> *Not the finest craftsmanship, but they'll do in a pinch.*

## Kadu's Wonderous Scrolls
- The shop was immaculate and empty. An enchantment on the door noted that the proprietor will be back some time later. 

## Stables

## Council Hall

## Speaker's Palace

## Armory
- Sheriff: [[Markham Southwell]]

## The Hooked Knucklehead
- Tavern keeper is a half-orc who speaks Thieves Cant.
- [[Zhentarim]] managed.

## The Northlook
- Tavern keeper: [[Scramsaxx]]

## Kelvin's Comfort 
- Tavern keeper: [[Ogden Flamebeard]]

## House of the Morninglord
- Temple of [Lathander](https://forgottenrealms.fandom.com/wiki/Lathander) and shrine to [Amauntor](https://forgottenrealms.fandom.com/wiki/Amaunator), deities and aspects of the Sun, Spring, and Order.
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
![[heraldry - Bryn Shander.png| 300]]