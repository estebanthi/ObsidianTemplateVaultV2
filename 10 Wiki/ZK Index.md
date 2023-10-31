---
tags:
  - dashboard
---
# ZK Index
---

## MOCs
```dataview
LIST
FROM #wiki/notes/moc 
WHERE file.name != "MOC"
SORT file.name ASC
```

## Notes without MOCs
```dataview
LIST
FROM "10 Wiki/12 Notes"
WHERE contains(related-mocs, null)
``````

## Embryos
```dataview
LIST
FROM #wiki/notes/embryo AND "10 Wiki"
```

## Need work
```dataview
LIST
FROM #wiki/meta/need-work 
```