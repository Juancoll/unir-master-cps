```dataview
TABLE WITHOUT ID
   ("![coverimg|100](" + cover + ")") as "Cover",
   file.link as file,
   author as Author,
   tags
FROM "library/items"
SORT file.name ASC
```

