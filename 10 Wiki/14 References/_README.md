This template vault just includes book and movies references. In my personal vault I have much more: Zotero references, articles, web pages, etc...

# Adding New References Types

## [[Learning Center]] and MOCs support
If you want your references notes to work with the [[Learning Center]], you should include the following properties:
- `consumed`: true or false
- `to-reconsume`: true or false
- `favorite`: true or false
- `rating`: higher = better
- `priority`: higher = most important

If you want your references to appear in your MOCs, you should include the property `related-mocs`.

## Linking wiki notes and references
If you want to link your references and your wiki notes, your references notes should include a Dataview query. See for example how [[Sample Note - 20231031032802|Sample Note]] appears under "Related Notes" in [[21 Lessons for the 21st Century - 1473554713|21 Lessons for the 21st Century]] thanks to the following query:

```
LIST 
FROM "10 Wiki"
WHERE contains(references, [[21 Lessons for the 21st Century - 1473554713]])
```

## Organization and index
For organization purpose, I recommend tagging your references, and this way it shows the reference type in the [[Learning Center]].

I also like to create index notes for similar references. It can be done with Dataview queries (see [[Books]] or [[Movies and TV Shows]]).

## Templates
Of course, you should create templates for each reference types you want in your vault to make the above process easier.


[[10 Wiki/_README|<- BACK]]