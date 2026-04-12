# Vocabulary Index

```dataview
TABLE file.name as "Topic", tags
FROM "01 Vocabulary"
WHERE contains(file.name, " ")
SORT file.name
```
