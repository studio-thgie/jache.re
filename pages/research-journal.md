---
title: "Research Journal"
authors: "Adrian Demleitner"
---
# Research Journal
<table class="dataview table-view-table"><thead class="table-view-thead"><tr class="table-view-tr-header"><th class="table-view-th"><span>File</span><span class="dataview small-text">2</span></th><th class="table-view-th"><span>title</span></th><th class="table-view-th"><span>date</span></th><th class="table-view-th"><span>tags</span></th></tr></thead><tbody class="table-view-tbody"><tr><td><span><a aria-label-position="top" aria-label="journal/2023-02-04-rj.md" data-href="journal/2023-02-04-rj.md" href="journal/2023-02-04-rj.md" class="internal-link" target="_blank" rel="noopener">2023-02-04-rj</a></span></td><td><span>4th Feb 2023</span></td><td>February 04, 2023</td><td><ul class="dataview dataview-ul dataview-result-list-ul"><li class="dataview-result-list-li"><span>research journal</span></li><li class="dataview-result-list-li"><span>literature review</span></li></ul></td></tr><tr><td><span><a aria-label-position="top" aria-label="journal/2023-02-01-rj.md" data-href="journal/2023-02-01-rj.md" href="journal/2023-02-01-rj.md" class="internal-link" target="_blank" rel="noopener">2023-02-01-rj</a></span></td><td><span>1st Feb 2023</span></td><td>February 01, 2023</td><td><ul class="dataview dataview-ul dataview-result-list-ul"><li class="dataview-result-list-li"><span>research journal</span></li><li class="dataview-result-list-li"><span>goals</span></li></ul></td></tr></tbody></table>

```dataview
TABLE title, date, tags
FROM "journal"
WHERE contains(tags, "research journal")
SORT date DESC
```
