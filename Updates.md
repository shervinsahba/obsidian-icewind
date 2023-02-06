---
dg-publish: false
---

## Updates
```dataview
TABLE WITHOUT ID 
	file.link as "Files updated in the last 2 weeks",
	file.mtime AS ""
WHERE dg-publish = True
AND date(today) - file.mtime < dur(14 days)
SORT file.mtime DESC
```

