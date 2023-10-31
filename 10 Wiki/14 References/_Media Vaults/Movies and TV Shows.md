---
tags: index
---
# Movies and TV Shows
---
```dataview
TABLE
("![|100](" + image + ")") as Cover, author as Author, rating as Rating
FROM #wiki/references/omdb
WHERE file.name != "OMDb Reference"
SORT Rating desc
```