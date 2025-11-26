---
title: Welcome to Jeff's Second Brain
index: "false"
---
> [!faq]- What Is This?
>  
![[What_Is_This]]
## Notebook Index

```dataview
TABLE WITHOUT ID link(file.name) AS "Page", file.mtime AS "Last Updated"
WHERE index != "false" AND file.folder != "fileClass" AND file.folder != "templates"
SORT file.mtime DESC
```

### Current Categories:

<!-- QueryToSerialize: TABLE WHERE contains(file.folder, "/") = false AND file.folder != "fileClass" AND file.folder != "" GROUP BY link(file.folder) AS "Category" -->
<!-- SerializedQuery: TABLE WHERE contains(file.folder, "/") = false AND file.folder != "fileClass" AND file.folder != "" GROUP BY link(file.folder) AS "Category" -->

| Category                   |
| -------------------------- |
| [[Art_Things\|Art_Things]] |
| [[Day_to_Day\|Day_to_Day]] |
| [[Growth\|Growth]]         |
| [[Math\|Math]]             |
| [[Misc\|Misc]]             |
| [[References\|References]] |
| [[The_World\|The_World]]   |
<!-- SerializedQuery END -->
