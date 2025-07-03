---
acid: 01.00
---
# `$= moment().format("MMMM Do[, ] YYYY")`

### Recent Notes
```dataview
LIST FROM "/"
WHERE date AND date(today) - date(date) < dur(7 days)
SORT date(date) DESC
```
