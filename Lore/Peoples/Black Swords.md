---
dg-publish: true
---
The Black Swords the cult of [[Levistus]], the Archduke of the 5th layer of Baetor, the Nine Hells. [[Kadroth]] and [[Hethyl Arkorran]] had been acting in leadership roles in [[Caer Dineval]] when the party first arrived. The wizard [[Avarice]] has ties to this group and had lodging in their keep.

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```