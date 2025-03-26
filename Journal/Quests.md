---
dg-publish: true
dg-hide-in-graph: true
---

# Quest Tag Overview
Quests are represented by tags throughout this vault. Here are all the tags, sorted by recency. Some tags, like that for battles, are not meant to track quests. 
```dataview
TABLE WITHOUT ID 
	(tag + "(" + length(rows.file.link) + ")") AS "Quest Tag",
	join(reverse(rows.file.link), ", ") AS Session 
FROM "Journal"
FLATTEN file.tags AS tag
GROUP BY tag
SORT reverse(rows.file.link) DESC
```


# Active Main Quests
## The Chosen
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheChosen   
FLATTEN x WHERE contains(x,"TheChosen") 
SORT file.name ASC
```
## The Rime of the Frostmaiden
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheRimeoftheFrostmaiden   
FLATTEN x WHERE contains(x,"TheRimeoftheFrostmaiden") 
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
## Reghed Tribes
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #ReghedTribes  
FLATTEN x WHERE contains(x,"ReghedTribes") 
SORT file.name ASC
```

# Active Side Quests
## The Devil You Know
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheDevilYouKnow  
FLATTEN x WHERE contains(x,"TheDevilYouKnow") 
SORT file.name ASC
```
## Ten Towns Things
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TenTownsThings   
FLATTEN x WHERE contains(x,"TenTownsThings") 
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
## Golem Guardian
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #GolemGuardian  
FLATTEN x WHERE contains(x,"GolemGuardian") 
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
## Four Gods of Fury
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #FourGodsofFury    
FLATTEN x WHERE contains(x,"FourGodsofFury") 
SORT file.name ASC
```
## KrakenClimateArena
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #KrakenClimateArena   
FLATTEN x WHERE contains(x,"KrakenClimateArena") 
SORT file.name ASC
```
## The Frozen Games
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #TheFrozenGames  
FLATTEN x WHERE contains(x,"TheFrozenGames") 
SORT file.name ASC
```
## Oyaminartok
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #Oyaminartok  
FLATTEN x WHERE contains(x,"Oyaminartok") 
SORT file.name ASC
```
## Kuldahar
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #Kuldahar   
FLATTEN x WHERE contains(x,"Kuldahar") 
SORT file.name ASC
```
## Feast of the Moon
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #FeastOfTheMoon   
FLATTEN x WHERE contains(x,"FeastOfTheMoon") 
SORT file.name ASC
```
## Destruction's Light
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #DestructionsLight    
FLATTEN x WHERE contains(x,"DestructionsLight") 
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
## Underdark Expedition
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS ""
FROM #UnderdarkExpedition  
FLATTEN x WHERE contains(x,"UnderdarkExpedition") 
SORT file.name ASC
```
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
[[Home]] | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb) | [[Characters]] |  [[Chronicles]]  | [[Loot]] | [[Quests]]  | [[XP]]