---
limit: 20
mapWithTag: true
icon: globe
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: 
savedViews: []
favoriteView: 
fieldsOrder:
  - 1nEZuZ
version: "2.8"
fields:
  - name: countries
    type: Multi
    options:
      sourceType: ValuesFromDVQuery
      valuesList: {}
      valuesFromDVQuery: dv.pages("#Country").file.name
    path: ""
    id: 1nEZuZ
---
```dataviewjs
dv.pages("#Country").file.name
```
