---
dg-publish: true
---
```dataview
TABLE WITHOUT ID 
	file.link as "Session",
	summary AS "Chronicle" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles"
SORT file.name DESC
```

[[Icewind Quest | Return to homepage.]]