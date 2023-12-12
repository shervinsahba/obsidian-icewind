---
dg-publish: true
---
![[heraldry - Easthaven.png|300]]
![[map-Easthaven.jpg|1000]]
# Characters

```dataview 
TABLE WITHOUT ID
  file.link AS "Character", role AS "Role", race AS "Race", age AS "Age", gender AS "Gender", descriptors AS "Descriptors"
FROM "Characters/Ten Towns/Easthaven"
SORT file.name
```

# Locations
## Town Hall
A two-story building that housed venues for gatherings, public records storage, and the local library. While the town was not truly lawless, the locals said that "anything goes in Easthaven." Pickpocketing was decidedly made legal throughout the town's history. Neverthless, convicts were routinely offered as sacrifice to the Frostmaiden, honoring an old tradition, and Easthaven could readily assemble a militia approximately 150 to 200 warriors strong.

## White Lady Inn
Named after the cryptid [[White Lady]]. The Lady died while her husband was away, amassing a fortune for their shared future, and after her death, appeared at shore of the lake where they first met. The proprietor's name is [[Bartaban]].

## The Wet Trout
The largest and loudest of the town's taverns.

## Easthaven Ferry
A once-successful business that had to be closed due to the Everlasting Rime.

## Stables

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
