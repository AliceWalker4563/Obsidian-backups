```dataview
TABLE type
FROM "HISTOLOGY"
WHERE contains(type, "structure")
```









# How to write queries in DQL

`dataview
`[FORMAT] [fields]
`FROM [source]`
`WHERE [conditions]`
`SORT [field] [ASC/DESC]`

### 1. FORMAT

`LIST` - a bulleted list of matching pages
`TABLE` - spreadsheet style table with columns
`TASK` - pulls todos out of notes
`CALENDAR` - displays daily notes on a calendar

### 2. SOURCE

`FROM #tag` - notes with this tag
`FROM Folder/Subfolder` - notes in this folder
`FROM [[File]]` - notes linked to this file
`AND` can be written to combine

### 3. WHERE and SORT

`WHERE` - filters files based on criteria
`SORT` - changes the order of the results

