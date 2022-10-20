---
baseofOperations: ["",]
leaders: [""]
alignment: [""]
enemies: [""]
tags:
  - "dnd"
  - "organization"
aliases:
type: "organization"
---
# [[<%tp.file.title%>]]
<% await tp.file.move("/dnd/organizations/" + tp.file.title) %>
**Summary**:: 

## Description:
Lorem ipsum..

## Organizational Structure:

### Leader: [[<% await tp.frontmatter.leaders%>]]

### Other members of <%tp.file.title%>
* . . .



---
```ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```