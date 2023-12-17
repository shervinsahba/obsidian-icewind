---
dg-publish: true
---
![[heraldry - Zhentarim.png|300]]

Previously known as the Black Network, the Zhentarim are a mercenary company and greater mercantile organization in Faerûn, who, over their 200 years of existence, have had a storied history as a cadre of self-serving thieves, spies, assassins and malevolent wizards.

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```