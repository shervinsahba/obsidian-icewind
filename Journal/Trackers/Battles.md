---
dg-publish: true
---
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS "Battle Description" FROM #battle 
FLATTEN x WHERE contains(x,"#battle") 
SORT file.name DESC
```

---

Journal: **[[Chronicles]] | [[Quests]] |  [[Characters]] | Battles | [[XP]] | [[Loot]]**

[[Icewind Quest | Return to homepage.]]