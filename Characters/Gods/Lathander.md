---
dg-publish: true
role: God of Dawn
race: God
---

> [!info]+
> ## Lathander, God of Rebirth and Renewal
> ### Morninglord, Dawnbringer
> ![[symbol_of_lathander.png]]

> Lathander was a Faerûnian greater god with a vast portfolio including birth, renewal, spring and youth, as well as athletics, self-perfection, vitality and creativity. The Morninglord was symbolized by the rising sun, but rather than being the god of the sun itself, he was the god of dawn, which represented the potential of a new day. A god of hope and beginnings, Lathander's name was invoked at the start of new endeavors, whether sealing a new deal, or setting out on a new journey.


```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
