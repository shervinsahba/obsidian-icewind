---
dg-publish: true
dg-hide-in-graph: true
---

## Active Quests

```dataview
TABLE WITHOUT ID 
	tag AS "Main Quests",
	join(reverse(rows.file.link), ", ") + " (" + length(rows.file.link) + ")" AS "Sessions"
FROM "Journal"
FLATTEN file.tags AS tag
WHERE contains(["#TheRimeoftheFrostmaiden","#TheChosen"], tag)
GROUP BY tag
SORT reverse(rows.file.link) DESC
```

```dataview
TABLE WITHOUT ID 
	tag AS "Side Quests",
	join(reverse(rows.file.link), ", ") + " (" + length(rows.file.link) + ")" AS "Sessions"
FROM "Journal"
FLATTEN file.tags AS tag
WHERE contains(["#FrostburnBlade","#TenTownsTreks","#TheDevilYouKnow"], tag)
GROUP BY tag
SORT reverse(rows.file.link) DESC
```

```dataview
TABLE WITHOUT ID 
	tag AS "Cold Quests",
	join(reverse(rows.file.link), ", ") + " (" + length(rows.file.link) + ")" AS "Sessions"
FROM "Journal"
FLATTEN file.tags AS tag
WHERE contains(["#NatureSpirits","#TheRamshackle","#GolemGuardian","#ChardalynBerserkers"], tag)
GROUP BY tag
SORT reverse(rows.file.link) DESC
```

```dataview
TABLE WITHOUT ID 
	tag AS "Completed Quests",
	join(reverse(rows.file.link), ", ") + " (" + length(rows.file.link) + ")" AS "Sessions"
FROM "Journal"
FLATTEN file.tags AS tag
WHERE !contains(["#TheRimeoftheFrostmaiden","#TheChosen"], tag)
WHERE !contains(["#FrostburnBlade","#TenTownsTreks","#TheDevilYouKnow"], tag)
WHERE !contains(["#NatureSpirits","#TheRamshackle","#GolemGuardian","#ChardalynBerserkers"], tag)
WHERE !contains(["#battle"], tag)
GROUP BY tag
SORT reverse(rows.file.link) DESC
```

---
[[Home]] | [Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb) | [[Characters]] |  [[Chronicles]]  | [[Loot]] | [[Quests]]  | [[XP]]