---
dg-publish: true
---
![[map-Lonelywood.jpg|600]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race"
FROM "NPCs/Ten Towns/Lonelywood"
SORT file.name
```

# Locations
## Ramshackle Inn
A dilapidated inn, once run by [[DeGrootz Ramshackle]]. DeGrootz was found dead, hanging, in his inn about a year and half ago. During the relentless winter, the roof has since collapsed.

## Lucky Liar

## The Happy Scrimshander
# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Details" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
![[heraldry - Lonelywood.png|300]]