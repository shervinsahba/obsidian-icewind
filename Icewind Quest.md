---
dg-home: true
dg-publish: true
---

## Welcome to Icewind Dale
![[dd-rime-of-the-frostmaiden-art.jpg| 600]]

# Journal

## [[Chronicles]] | [[Quests]] | [[XP]] | [[Battles]] | [[Loot]]

```dataview
TABLE WITHOUT ID 
	file.link as "Recent Sessions",
	summary AS "Chronicle" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot"  AND file.name != "Chronicles"
SORT file.name DESC
LIMIT 3
```

# About
This site was made as a Zettelkasten style notebook using [obsidian.md](https://obsidian.md) alongside the plugins [obsidian-dataview](https://blacksmithgu.github.io/obsidian-dataview/) and [obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden). Theme: [vileplume](https://github.com/hungsu/vileplume-obsidian).

### source code
[github.com/shervinsahba/obsidian-icewind](https://github.com/shervinsahba/obsidian-icewind)
Here is the source code for the vault itself, along with a README about the notebook, plugins, and workflow in using this system for your own purposes. Note: the `.obsidian` folder has been purposely omitted, so you'll need to add the aforementioned plugins and theming.

## Junji's Tavern
Junji's Tavern is our gaming group. Junji Ito is my dog ![[junji.png]].