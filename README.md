# icewind.quest

## obsidian-icewind

[icewind.quest](https://icewind.quest) is a hosted Zettelkasten-style notebook using [obsidian.md](https://obsidian.md) alongside the plugins [obsidian-dataview](https://blacksmithgu.github.io/obsidian-dataview/) and [obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden), which respectively handle data manipulations and help turn the vault into a website.

If you're familiar with obsidian, the main takeaways are (1) you can easily evolve your notebook into a website with the obsidian-digital-garden plugin and (2) the scripting in my notebook does a *lot* of heavy lifting when it comes to tracking reoccuring entities, in this case characters, events, and locations in a Dungeons and Dragon 5e campaign of [Icewind Dale: Rime of the Frostmaiden](https://en.wikipedia.org/wiki/Icewind_Dale:_Rime_of_the_Frostmaiden). With a minimal amount of tagging, obsidian-dataview scripts allow for self-generated character pages.

## the workflow

The workflow then becomes rather simple to upkeep. Keeping the context of a D&D campaign, upkeep mostly entails [logging each new playing session](https://github.com/shervinsahba/obsidian-icewind/tree/main/Chronicles). For example, for each new character the party encounters:
- create a NPC character page using the NPC [template](https://github.com/shervinsahba/obsidian-icewind/tree/main/_templates)
- tag the character during Session logs

The dataview script will then scrape all Sessions for the linked character and populate their page with a log of encounters. The same idea is repeated for quests, battles, and locations. Simple!

## the results

Click the image link to check the site. This was a quick little side project, but if you can think of any improvements, raise an issue.

[![https://icewind.quest](icewindquest_sample.png)](https://icewind.quest)

