---
title: Draw Steel на русском
---
## Статус перевода
---
### Происхождения
```dataview
TABLE description as Описание, lore as Рассказ, traits as Черты
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "ancestry"
SORT file.name ASC
```
### Классы
```dataview
TABLE row["1st lvl"] as "1 лвл", row["2nd lvl"] as "2 лвл", row["3rd lvl"] as "3 лвл", row["4th lvl"] as "4 лвл", row["5th lvl"] as "5 лвл", row["6th lvl"] as "6 лвл", row["7th lvl"] as "7 лвл", row["8th lvl"] as "8 лвл", row["9th lvl"] as "9 лвл", row["10th lvl"] as "10 лвл"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "class"
SORT file.name ASC
```
### Карьеры
```dataview
TABLE description as Описание, benefits as Преимущества, incidents as Инциденты
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "career"
SORT file.name ASC
```
### Навыки
```dataview
TABLE status as Статус
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "skill"
SORT ASC
```
### Бонусы
```dataview
TABLE status as Статус
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND file.name != "index" AND file.name != "README"
WHERE type = "perks"
SORT ASC
```