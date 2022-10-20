---
type: "npc"
tags:
  - "dnd"
  - "npc"

date_added: <% tp.date.now("YYYY-MM-DD") %>
---
# [[<% tp.file.title %>]]

```ad-example
title: [[<% tp.file.title %>]]  Raw Data:
collapse: closed

**summary**:: 

**campaign**:: 

**aliases**:: 

**alignment**::

**organization**::

**location**::

**race**::

**gender**::

**class**::

```
```ad-quote
title: - *<%tp.file.title%>:*
collapse: open

*`= this.summary`*
```

```ad-hint
title: Art
collapse: open

**character_art**:: 
```

```ad-summary
title: COGAS at a Glance
collapse: open


**Color**:: 

**Occupation**::

**Goals**::

**Attitude**::

**Stake**::

```

```ad-caution
title: Statblock

# Statblock:

```


---
````ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```
````


<% await tp.file.move("/dnd/npc/" + tp.file.title) %>