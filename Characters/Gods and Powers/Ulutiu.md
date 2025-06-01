---
dg-publish: true
role: Demigod of Glaciers
age: Ancient
race: Giant-kin
gender: Man
descriptors: [Peaceful, Wild, Contemplative]
status: EXILED
---
Ulutiu was the demigod of glaciers, frozen seas, polar environments, and arctic dwellers and the father of the giant-kin races like verbeegs and firbolgs. **The Eternal Sleeper was in a state of voluntarily-induced slumber, not quite dead and alive enough to grant spells but floating unconscious through the Astral Plane.**

Giants were descended from all-father Annam and his wife, the goddess Olthea. The giant-kin, though, descended from Olthea's affair with Ulutia. Ancient giant carvings circa -2500 DR show Annam's retribution -- slaying Ulutiu -- but in reality Ulutia made a bargain to enter an eternal slumber, exiling himself to the Astral Plane.

**Ulutiu fell deep into the Cold Ocean, where his amulet began to freeze the waters around him. The ice spreading from Ulutiu's amulet formed the Endless Ice Sea and the Great Glacier, which destroyed much of what remained of Ostoria.**

Ulutiu's true origins were unknown. Some believed he may originally have been mortal while others believed he was always divine, whether he was an avatar of some other god or a refugee entity from another world.

![[ulutia.png]]




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
