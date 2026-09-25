```dataview
TABLE topic, type
FROM "HISTOLOGY"
WHERE contains(type, "tissue") and contains(topic, "muscle")
```
