---
tags:
  - dashboard
---
# Learning Center
---
I use this note to keep track of the things I need to read/watch/listen. It allows me to capture references I can't consume instantly and don't forget them.

## Watch list
```dataview
TABLE
tags as Type,
priority as Priority
FROM "10 Wiki/14 References"
SORT priority descending
WHERE consumed != true AND contains(file.path, "_Media Vaults") != true
```

## To reconsume
```dataview
TABLE
tags as Type,
author as Author
FROM "10 Wiki/14 References"
WHERE contains(to-reconsume, true)
```


## Consumed

### Favorites
```dataview
TABLE
tags as Type,
author as Author
FROM "10 Wiki/14 References"
WHERE contains(favorite, true)
```

### All
```dataview
TABLE
tags as Type, rating as Rating
FROM "10 Wiki/14 References"
WHERE contains(file.path, "_Media Vaults") != true
SORT Rating desc
```

