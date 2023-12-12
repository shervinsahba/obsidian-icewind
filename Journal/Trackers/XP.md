---
dg-publish: true
---
**TOTAL**: 5350 since session 17.

```dataview
TABLE WITHOUT ID
	split(xp, " ~ ")[0] AS "XP",
	split(xp, " ~ ")[1] AS "Experience",
	file.link AS "Session"
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles" AND file.name != "Characters"
FLATTEN xp
FLATTEN sum(rows.xp) AS Total
SORT file.name DESC
```

![[characteradvancement.png]]

---

Journal: **[[Chronicles]] | [[Quests]] |  [[Characters]] | [[Battles]] | XP | [[Loot]]  | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb)**

[[Icewind Quest | Return to homepage.]]