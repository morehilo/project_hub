# DFIR Dashboard

## Sherlocks in Progress

```dataview
TABLE difficulty as "Difficulty"
FROM "01-Sherlocks/Active"
SORT file.name ASC
```


## Sherlocks Completed

```dataview
TABLE difficulty as "Difficulty"
FROM "01-Sherlocks/Completed"
SORT difficulty ASC, file.name ASC
```

