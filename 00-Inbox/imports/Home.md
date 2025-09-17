---
created: 2023-03-15T22:54
updated: 2025-07-15T10:06
---

## Vault Info
| 🗄️ Recent file updates | To Read | Favourites  |
| --- | --- | --- |
| `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)` | `$=dv.list(dv.pages('"ReadItLater" and -#read').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)` | `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)` |


〽️ Stats
	-  File Count: `$=dv.pages().length`
	-  Project Count: `$=dv.pages('"010 Projects"').length`

## Active Items
### Open Projects
`$=dv.list(dv.pages('"010 Projects"').sort(f=>f.file.mtime.ts,"desc").limit(6).file.link)` 

### Open Tasks
`$=dv.taskList(dv.pages().file.tasks.where(t => !t.completed && !t.cancelled))` 
