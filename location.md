---
aliases:
type: "location"
tags:
  - "dnd"
  - "location"
---
# <%tp.file.title%>
*(Remember: Choose an evocative title)*
```ad-example
title: [[<% tp.file.title %>]]  Raw Data:
collapse: closed

**summary**:: ""
**location**:: 
**environment**:: 
**campaign::** 
```

# Features of <% tp.file.title %>:
```ad-note
title: Three Fantastic Aspects of <%tp.file.title%>

*Focus on: scale. Big things, old things, vast things. Is <%tp.file.title%> relevant to a character's background?*

1. -

2. -

3. -

```

# <% tp.file.title %> Map(s):
````ad-info
title: Map
collapse: open

```leaflet
id: "<%tp.file.title%>" 
image:   
defaultZoom: 6 
zoomDelta: .5 
scale: 145
```
````

```ad-info
title: Regional Map
collapse: open
![[Faerun#Faerun Map|...]]
```


---
````ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```
````

<% await tp.file.move("/dnd/location/" + tp.file.title) %>
