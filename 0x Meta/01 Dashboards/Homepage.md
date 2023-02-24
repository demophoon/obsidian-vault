---
acid: 01.00
---
# `$= moment().format("MMMM Do[, ] YYYY")`

```button
name New Note
type command
action Create new note
color blue
```

```dataview
LIST FROM "/"
WHERE date(today) - date(date) < dur(7 days) OR
      date(today) - file.mtime < dur(7 days)
SORT date(date) DESC
```
