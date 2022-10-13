---
title: 
sources: 
uid: 202210030905
aliases: [Dataview – Ideas Bin]
tags:
-
post_nr:
post_status: draft
_post_date: YYYY-MM-DD HH:MM:SS
cssclass: wide-page
taxonomy:
    category:
        - Digital Garden
    post_tag:
        -
---

# All Notes
```dataview
TABLE 
post_nr AS Nr,
post_status AS Status,
post_date AS "Publish Date",
sources[0] AS Source,
taxonomy["category"] as Category,
file.outlinks AS "Out Links",
file.inlinks AS "In Links"
FROM "Ideas Bin"
SORT Category DESC
```
# Digital Garden Notes
# Ready for Publication
```dataview
TABLE 
post_status AS Status,
post_date AS "Publish Date",
sources[0] AS Source,
taxonomy["category"] as Category,
file.outlinks AS "Out Links"
FROM "Postdrafts"
```





