---
dg-home: true
dg-publish: true
---

![[map-poster.jpg]]

```dataview
TABLE WITHOUT ID 
	file.link as "Session",
	summary AS "Chronicle" 
FROM "Chronicles" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "Journal" AND file.name != "XP"
SORT file.name DESC
```

```dataview
TABLE WITHOUT ID 
	file.link as "Logs"
FROM "Chronicles" WHERE file.name = "Quests" OR file.name = "Battles" OR file.name = "Journal" OR file.name = "XP"
```
