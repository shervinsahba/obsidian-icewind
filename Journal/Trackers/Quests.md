---
dg-publish: true
dg-hide-in-graph: true
---
# Quest Tag Overview
Quests are represented by tags throughout this vault. Here are all the tags, sorted by recency.
```dataview
TABLE WITHOUT ID 
	(tag + "(" + length(rows.file.link) + ")") AS "Quest Tag",
	join(reverse(rows.file.link), ", ") AS Session
FROM "Journal"
FLATTEN file.tags AS tag
GROUP BY tag
SORT reverse(rows.file.link) DESC
```


# Active Quests
## The Rime of the Frostmaiden
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheRimeoftheFrostmaiden   
FLATTEN x WHERE contains(x,"TheRimeoftheFrostmaiden") 
SORT file.name ASC
```
## A Duergar Plot
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ADuergarPlot  
FLATTEN x WHERE contains(x,"ADuergarPlot") 
SORT file.name ASC
```
## The Forgotten Realm
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheForgottenRealm  
FLATTEN x WHERE contains(x,"TheForgottenRealm") 
SORT file.name ASC
```
## Frostburn Blade
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #FrostburnBlade  
FLATTEN x WHERE contains(x,"FrostburnBlade") 
SORT file.name ASC
```
## Nature Spirits
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #NatureSpirits 
FLATTEN x WHERE contains(x,"NatureSpirits") 
SORT file.name ASC
```
## The Signal of the Id
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheSignal 
FLATTEN x WHERE contains(x,"TheSignal") 
SORT file.name ASC
```
## The Ramshackle
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheRamshackle 
FLATTEN x WHERE contains(x,"TheRamshackle") 
SORT file.name ASC
```


# Completed Quests
## The Council
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheCouncil   
FLATTEN x WHERE contains(x,"TheCouncil") 
SORT file.name ASC
```
## The Vault
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheVault   
FLATTEN x WHERE contains(x,"TheVault") 
SORT file.name ASC
```
## Prisoner 13
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #Prisoner13  
FLATTEN x WHERE contains(x,"Prisoner13") 
SORT file.name ASC
```
## Dzaan is Dead
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #DzaanIsDead 
FLATTEN x WHERE contains(x,"DzaanIsDead") 
SORT file.name ASC
```
## The Lost Spire
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheLostSpire  
FLATTEN x WHERE contains(x,"TheLostSpire") 
SORT file.name ASC
```
## Prisoner237
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #Prisoner237  
FLATTEN x WHERE contains(x,"Prisoner237") 
SORT file.name ASC
```
## RevelsEnd
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #RevelsEnd  
FLATTEN x WHERE contains(x,"RevelsEnd") 
SORT file.name ASC
```
## The Whale Hunters and Angajuk's Bell
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #WhaleHunters OR #AngajuksBell 
FLATTEN x WHERE contains(x,"WhaleHunters") OR contains(x,"AngajuksBell")
SORT file.name ASC
```
## The Dark Duchess
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #DarkDuchess 
FLATTEN x WHERE contains(x,"DarkDuchess") 
SORT file.name ASC
```
## Black Swords
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #BlackSwords  
FLATTEN x WHERE contains(x,"BlackSwords") 
SORT file.name ASC
```
## Chardalyn Caper
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ChardalynCaper  
FLATTEN x WHERE contains(x,"ChardalynCaper") 
SORT file.name ASC
```
## Cauldron Caper
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #CauldronCaper  
FLATTEN x WHERE contains(x,"CauldronCaper") 
SORT file.name ASC
```
## White Lady Seance
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #WhiteLadySeance  
FLATTEN x WHERE contains(x,"WhiteLadySeance") 
SORT file.name ASC
```
## The Mead Must Flow
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheMeadMustFlow 
FLATTEN x WHERE contains(x,"TheMeadMustFlow") 
SORT file.name ASC
```
## Cold Hearted Killer
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ColdHeartedKiller 
FLATTEN x WHERE contains(x,"ColdHeartedKiller") 
SORT file.name ASC
```
## Lake Monster
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #LakeMonster 
FLATTEN x WHERE contains(x,"LakeMonster") 
SORT file.name ASC
```
## The Golden Dawn
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS "" FROM #TheGoldenDawn 
FLATTEN x WHERE contains(x,"GoldenDawn") 
SORT file.name ASC
```
## The White Moose
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheWhiteMoose 
FLATTEN x WHERE contains(x,"TheWhiteMoose") 
SORT file.name ASC
```
## A Beautiful Mine
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ABeautifulMine 
FLATTEN x WHERE contains(x,"ABeautifulMine") 
SORT file.name ASC
```
## Mountain Climb
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #MountainClimb
FLATTEN x WHERE contains(x,"MountainClimb") 
SORT file.name ASC
```
## Armored Corps
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ArmoredCorps 
FLATTEN x WHERE contains(x,"ArmoredCorps") 
SORT file.name ASC
```
## Frosted Mugs
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS "" 
FROM #FrostedMugs 
FLATTEN x WHERE contains(x,"FrostedMugs") 
SORT file.name ASC
```
## Special Delivery
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #SpecialDelivery
FLATTEN x WHERE contains(x,"SpecialDelivery") 
SORT file.name ASC
```



---

Journal: **[[Chronicles]] | Quests |  [[Characters]] | [[Battles]] | [[XP]] | [[Loot]]  | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb)**

[[Icewind Quest | Return to homepage.]]
