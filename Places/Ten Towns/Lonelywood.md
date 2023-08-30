---
dg-publish: true
---
![[heraldry - Lonelywood.png|300]]
![[map-Lonelywood.jpg|600]]
# Characters
```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Lonelywood"
SORT file.name
```

# Locations
## Ramshackle Inn
A dilapidated inn, once run by [[DeGrootz Ramshackle]]. DeGrootz was found dead, hanging, in his inn about a year and half ago. During the relentless winter, the roof has since collapsed.
## Lucky Liar
Local tavern, opened a decade ago by the enigmatic and well-informed [[Danae Xotal]].
## The Happy Scrimshander
An artisan supply store run by [[Iriskree Harrowhill]], retired and doughty spinster assassin.
## Nimsy Huddle's House
Speaker [[Nimsy Huddle]] is a welcoming host. Since the town has no inn, she offers her attic to travelers.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
