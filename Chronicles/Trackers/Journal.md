---

```dataview
TABLE WITHOUT ID
	file.link AS "Session",
	summary AS "Chronicle", x AS "Details" FROM "Chronicles"
	WHERE file.name != "Battles" AND file.name != "Quests" AND file.name != "Journal" AND file.name != "XP"
SORT file.name DESC
```