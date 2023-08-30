---
dg-home: true
dg-publish: true
---

## Welcome to Icewind Dale
![[rotf_cover_art.jpg|600]]
# Journal
[[Chronicles]] | [[Quests]] | [[Battles]] | [[XP]] | [[Loot]]
```dataview
TABLE WITHOUT ID 
	file.link as "Recent Sessions",
	summary AS "Chronicle" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles"
SORT file.name DESC
LIMIT 3
```
# About
## About the site

This site was made as a [Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten) notebook using [obsidian.md](https://obsidian.md) alongside the plugins [obsidian-dataview](https://blacksmithgu.github.io/obsidian-dataview/) and [obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden). The theme is called [vileplume](https://github.com/hungsu/vileplume-obsidian).

Here's the **source code**: [github.com/shervinsahba/obsidian-icewind](https://github.com/shervinsahba/obsidian-icewind). There is a README about the notebook, plugins, and workflow in using this system for your own purposes. Note that the `.obsidian` folder has been purposely omitted, so you'll need to add the aforementioned plugins and theming.

Junji's Tavern is our gaming group. Junji Ito is my dog. ![[junji.png]]