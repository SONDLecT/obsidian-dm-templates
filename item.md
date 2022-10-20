---
date: "<%tp.date.now("YYYY-MM-DD")%>"
tags:
  - "dnd"
  - item
aliases:
  - ""
type: "item"
---
# <%tp.file.title%>

**summary**:: "


---
```ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```

