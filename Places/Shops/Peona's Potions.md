---
dg-publish: True
---

Your promising potion purveyor. [[Peona]], a dwarven alchemist, may be able to find magic items for you as well. Located in [[Easthaven]]. 

![[shop_peonas_potions.png]]

# Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Details" FROM "Journal"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
