---
dg-publish: true
---

**TOTAL**: 3300 since session 10.

```dataview
TABLE WITHOUT ID
	split(xp, " ~ ")[0] AS "XP",
	split(xp, " ~ ")[1] AS "Experience",
	file.link AS "Session"
	FROM "Chronicles" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP"
FLATTEN xp
FLATTEN sum(rows.xp) AS Total
```


![[characteradvancement.png]]

[[Icewind Quest | Return to homepage.]]