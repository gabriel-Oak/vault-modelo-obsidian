---
Data: 2024-06-20
Hora: 18:01
tags:
  - Indice
  - "#Home"
Ref: "[[README]]"
---
## Índice
```dataview
LIST
FROM #Indice AND #Ano 
WHERE 
	Data >= date(2023-12-31) 
	AND Data <=date(2025-01-01)
SORT file.name
```


