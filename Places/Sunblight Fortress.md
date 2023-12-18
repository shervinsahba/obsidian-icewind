---
dg-publish: True
---
The fortress of [[Xardorok Sunblight]]. He and his remaining children are planning a siege of Ten Towns, collecting [[chardalyn]] to forge weaponry in preparation.

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```