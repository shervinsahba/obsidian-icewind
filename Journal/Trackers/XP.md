---
dg-publish: true
---
**TOTAL**: 4600 since session 14.

```dataview
TABLE WITHOUT ID
	split(xp, " ~ ")[0] AS "XP",
	split(xp, " ~ ")[1] AS "Experience",
	file.link AS "Session"
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles" AND file.name != "Characters"
FLATTEN xp
FLATTEN sum(rows.xp) AS Total
```

![[characteradvancement.png]]

---

Journal: **[[Chronicles]] | [[Quests]] |  [[Characters]] | [[Battles]] | XP | [[Loot]]**

[[Icewind Quest | Return to homepage.]]