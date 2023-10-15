---
dg-publish: true
---
```dataview
TABLE WITHOUT ID 
	file.link as "Session",
	summary AS "Chronicle" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles" AND file.name != "Characters"
SORT file.name DESC
```

---

Journal: **Chronicles | [[Quests]] |  [[Characters]] | [[Battles]] | [[XP]] | [[Loot]]**

[[Icewind Quest | Return to homepage.]]