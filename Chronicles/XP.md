---
dg-publish: true
---

```dataview
TABLE WITHOUT ID
	file.link AS "Session", 
	split(xp, "xp")[0] AS "XP",
	split(xp, "xp")[1] AS "Experience"
	FROM "Chronicles"
FLATTEN xp WHERE contains(xp,"xp") 
SORT file.name DESC
```

