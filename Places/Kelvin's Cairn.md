---
dg-publish: true
---
![[place - Kelvins Cairn.png]]

# Lore
According to barbarian legends, the mountain is named for the frost giant hero Kelvin Duarol, who was slain here by the god Tempus. Tempus pulled rocks from the plain in a long ditch and piled them atop his fallen foe to mark his victory and to warn others of the fate of those who court the war gods wrath.

# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", note AS "Note"
FROM "NPCs/Kelvin's Cairn"
SORT file.name
```

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
![[heraldry - Clan Battlehammer.png]]