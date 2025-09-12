---
title: Draw Steel на русском
---
## Происхождения
```dataview
LIST
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "ancestry"
SORT ASC
```
## Классы
```dataview
LIST
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "class"
SORT ASC
```
### Карьеры
```dataview
LIST
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "career"
SORT file.name ASC
```
## Навыки
```dataview
LIST
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "skill"
SORT ASC
```
