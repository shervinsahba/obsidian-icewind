---
dg-publish: true
dg-hide-in-graph: true
---
```dataview
TABLE WITHOUT ID
	split(loot, " ~ ")[0] AS "Loot",
	split(loot, " ~ ")[1] AS "Description",
	file.link AS "Session"
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles" AND file.name != "Characters"
FLATTEN loot
```

---
[[Home]] | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb) | [[Characters]] |  [[Chronicles]]  | [[Loot]] | [[Quests]]  | [[XP]]