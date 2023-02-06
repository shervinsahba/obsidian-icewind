> [!cards|dataview]
> ```dataview
> TABLE WITHOUT ID
> 	"![|sban cover hmicro](" + image + ")" as Image,
> 	"**"+ file.link + "**" AS "Column Name",
> FROM "folder"
> SORT file.name
> LIMIT 10
> ```