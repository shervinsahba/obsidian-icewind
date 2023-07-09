---
dg-publish: true
---
```dataview
TABLE WITHOUT ID
	split(loot, " ~ ")[0] AS "Loot",
	split(loot, " ~ ")[1] AS "Description",
	file.link AS "Session"
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles"
FLATTEN loot
```


[[Icewind Quest | Return to homepage.]]