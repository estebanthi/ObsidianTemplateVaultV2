---
tags: index
---
# Books
---
```dataview
TABLE
("![|100](" + cover + ")") as Cover, author as Author, rating as Rating
FROM #wiki/references/book 
WHERE file.name != "Book Reference"
SORT Rating desc
```