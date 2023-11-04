---
dg-publish: true
---

The Arcane Brotherhood is a wizard guild that operated out of the Host Tower of the Arcane in [[Luskan]]. The organization is shrouded in mystery. Its most high-ranking members are unknown. The Brotherhood is primarily known for their vast accumulation of arcane lore. Those in power know the Brotherhood has vied for influence in the political and economic battlegrounds of the [[Sword Coast]]. 

Wizards flock to Luskan every year to petition to join the Brotherhood, but almost all are immediately rejected. The Brotherhood grows by recruiting like-minded wizards who would otherwise be rivals.

The people of [[Icewind Dale]] tend to be wary of the Brotherhood.
# Known Members and Happenings

- [[Vellynne Harpell]]
- [[Dzaan]]
- [[Avarice]]

```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "" FROM #ArcaneBrotherhood  
FLATTEN x WHERE contains(x,"ArcaneBrotherhood") 
SORT file.name DESC
```

## Vellynne Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,"Vellynne Harpell") 
SORT file.name DESC
```

## Dzaan Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,"Dzaan") 
SORT file.name DESC
```

## Avarice Happenings
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Journal"
FLATTEN x WHERE contains(x,"Avarice") 
SORT file.name DESC
```

# Images

Host Tower of the Arcane, in [[Luskan]].


![[place - Host Tower of the Arcane.png|400]]