---
dg-publish: True
---

Scrolls for sale! [[Kadu]] can also craft scrolls from spellbooks for half cost. They may be able to find magic items for you as well. Located in [[Bryn Shander]]. 

# Scrolls for sale

![[kaduscrolls.png]]


# Spellbooks found

**Astrix's Spellbook** (found in the top of Kelvin's Cairn during the Mountain Climb quest)

1.  Comprehend languages (R), Detect magic (R), Expeditious retreat, Shield, Tenser's floating disk (R)
2.  Alter self, Cloud of daggers, Scorching ray, Suggestion


# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
