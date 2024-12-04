---
dg-home: true
dg-publish: true
dg-hide-in-graph: true
dg-show-local-graph: false
dg-pinned: true
---
![[rotf_cover_art_banner_2.png]]

# Journal
**[Calendar](https://app.fantasy-calendar.com/calendars/38f9e3f5098bac1f655a4fb4241f35eb) | [[Characters]] |  [[Chronicles]]  | [[Loot]] | [[Quests]]  | [[XP]]**

```dataview
TABLE WITHOUT ID 
	default(file.link,"") + " " + summary AS "Session",
	saga AS "Saga" 
FROM "Journal" WHERE file.name != "Quests" AND file.name != "Battles" AND file.name != "XP" AND file.name != "Loot" AND file.name != "Characters" AND file.name != "Chronicles"
SORT file.name DESC
```

# Map 
[View full map](https://i.imgur.com/tQSddcj.jpeg) | [Interactive map](https://www.aidedd.org/atlas/index.php?map=I&l=1)
[![](https://i.imgur.com/tQSddcj.jpeg)](https://i.imgur.com/tQSddcj.jpeg)

# About
This site is an [Obsidian notebook](https://obsidian.md) reformatted for the web using the [digital-garden plugin](https://github.com/oleeskild/obsidian-digital-garden). To best chronicle my TTRPG campaign of Rime of the Frostmaiden, I've made liberal use of the [dataview plugin](https://blacksmithgu.github.io/obsidian-dataview/) to generate histories and callbacks, scraping information from my session notes to populate all the pages you see detailing happenings for characters and places. Check out the repository for more information: [github.com/shervinsahba/obsidian-icewind](https://github.com/shervinsahba/obsidian-icewind).

<div style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center;">
	<div style="display: flex; flex-direction: column; justify-content: center;align-items:center;">
		<img style="padding: 10px; border-radius: 15px;"  src="https://raw.githubusercontent.com/shervinsahba/obsidian-icewind/main/_attachments/slate_junji.png" />
		<center>My dog, Junji.<br>He's a good boy.</center>
	</div>
	<div style="display: flex; flex-direction: column; justify-content: center;align-items: center">
		<img style="padding: 10px; border-radius: 15px;" src="https://raw.githubusercontent.com/shervinsahba/obsidian-icewind/main/_attachments/slate_chum.png" />
			Me.<a href="https://syleria.netlify.app/">https://sahba.phd</a>
	</div>
</div>