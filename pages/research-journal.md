---
title: "Research Journal"
authors: "Adrian Demleitner"
---
# Research Journal

```dataview
TABLE title, date, tags
FROM "journal"
WHERE contains(tags, "research journal")
SORT date DESC
```
