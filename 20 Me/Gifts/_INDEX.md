---
dg-publish:
---
# Gifts
---
```dataview
TABLE
for as For, event as Event, date as Date
FROM "20 Me/Gifts"
WHERE file.name != "_INDEX"
SORT date desc
```