---
dg-publish: true
role: Silver miner
race: Dwarf
---

> [!info]+
> ## Dwarven Valley miner

> *We're the survivors of a group of dwarves tasked with
delivering a sled of iron ingots to Bryn Shander. A yeti
surprised us and killed a member of our group. The rest
of us fled as the yeti tore Oobok limb from limb. Now
we need someone to go back and get the sled for us. As
payment, we offer each of you a gemstone worth fifty
gold pieces. The friendship of the dwarves of Icewind
Dale can also be a boon in these harsh times. You'll need
snowshoes to make the trip in good time.*

```dataview
TABLE WITHOUT ID
	file.link AS "Note", 
	x AS "Interactions" FROM "Chronicles"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
