---
dg-publish: true
dg-hide-in-graph: true
---
```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	x AS "Battle Description" FROM #battle 
FLATTEN x WHERE contains(x,"#battle") 
SORT file.name DESC
```

---

Journal: **[[Chronicles]] | [[Quests]] |  [[Characters]] | Battles | [[XP]] | [[Loot]] | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb)**

[[Icewind Quest | Return to homepage.]]