---
dg-publish: true
---
Also known as black ice, a strange black material with the cold and luster of ice. The central stone in the [[Summer Star]] was made of black ice.

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```