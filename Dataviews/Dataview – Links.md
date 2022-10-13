---
uid: 202209171901
aliases: [Dataview Links]
cssclass: wide-page
---
```dataview
TABLE 
post_nr AS Nr,
post_status AS Status,
post_date AS "Publish Date",
sources[0] AS Source,
file.outlinks AS "Out Links",
file.inlinks AS "In Links"
FROM "Postdrafts"
SORT file.inlinks DESC
```