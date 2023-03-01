---
dg-publish: true
---

# Active Quests

## Mountain Climb
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #MountainClimb
FLATTEN x WHERE contains(x,"MountainClimb") 
SORT file.name DESC
```

## A Beautiful Mine
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #ABeautifulMine 
FLATTEN x WHERE contains(x,"ABeautifulMine") 
SORT file.name DESC
```

## TheMeadMustFlow
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #TheMeadMustFlow 
FLATTEN x WHERE contains(x,"TheMeadMustFlow") 
SORT file.name DESC
```

## Cold Hearted Killer
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #ColdHeartedKiller 
FLATTEN x WHERE contains(x,"ColdHeartedKiller") 
SORT file.name DESC
```


# Completed Quests
## ~~Armored Corps~~
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #ArmoredCorps 
FLATTEN x WHERE contains(x,"ArmoredCorps") 
SORT file.name DESC
```

## ~~Frosted Mugs~~
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #FrostedMugs 
FLATTEN x WHERE contains(x,"FrostedMugs") 
SORT file.name DESC
```

## ~~Special Delivery~~
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "" FROM #SpecialDelivery
FLATTEN x WHERE contains(x,"SpecialDelivery") 
SORT file.name DESC
```