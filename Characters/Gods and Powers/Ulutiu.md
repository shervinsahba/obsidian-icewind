---
dg-publish: true
role: Once Demigod of Glaciers
age: Ancient
race: Giant-kin
gender: Man
descriptors: [Firm, Protective, Contemplative]
status: EXILE
---
Ulutiu was the demigod of glaciers, frozen seas, polar environments, and arctic dwellers and the father of the giant-kin races like verbeegs and firbolgs. **The Eternal Sleeper was in a state of voluntarily-induced slumber, not quite dead and alive enough to grant spells but floating unconscious through the Astral Plane.**

Othea was the mother of the giant races of Faeriin and wife of Annam, father of the true giant races. She had children with Ulutiu, creating the giant-kin. When they were discovered, Ulutiu voluntarily exiled himself in exchange for Annam’s promise to spare his wife. He sank into the Cold Ocean with his ice necklace, causing it to freeze into the Great Glacier. Othea planned to reunite with Ulutiu but was slain by one of her sons, who could not venture onto the Great Glacier while his mother was alive. 

**Some say Ulutiu's fall into the Cold Sea creating the Endless Ice Sea and the Great Glacier. The spreading ice, whose source was said to be Ulutiu's amulet of blue and white crystals, destroyed much of what remained of Ostoria.**

Ulutiu's true origins were unknown. Some believed he may originally have been mortal while others believed he was always divine, whether he was an avatar of some other god or a refugee entity from another world.

He had few enemies and fewer allies. In his slumbering exile, his powers waned as modern and existing gods overtook his portfolio of cold and frost.

> [!info]+
> **`=this.role`**
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
