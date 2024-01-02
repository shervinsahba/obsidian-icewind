---
dg-publish: true
role: Archdevil, Duke of Stygia
age: Ancient
race: Fiend
gender: Male
descriptors: [Treacherous, Debonair, Evil]
---

> [!info]+
> **`=this.role`**
>  Lord of the Fifth, The Frozen Prince
> `=this.age` `=this.race` `=this.gender`
> `=this.descriptors` 

![[levistus.png]]

> Levistus was the Lord of Stygia, the fifth layer of the Nine Hells, a wasteland of ice. The self-titled "prince" was known for his treachery and was imprisoned in an ancient iceberg, often referred to as his tomb. Levistus's true appearance was widely unknown, as from the outside of his glacial prison he could only be seen as a small black blot a quarter-mile within the mountain of dark ice. In the days of his freedom, he wore loose, silken clothing and carried a shining rapier, now donning fanciful garments and other finery when meeting mortals in projected form. His holy symbol was a black sword embedded in ice.


```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,split(this.file.name," ")[0])
SORT file.name DESC
```
