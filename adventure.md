---
type: "adventure"
tags:
  - dnd
  - campaign
  - "<%tp.file.title%>"
ruleset: "5th Edition Dungeons and Dragons"
world: ""
---
# [[<%tp.file.title%>]]
<% await tp.file.move("/dnd/campaigns/" + tp.file.title) %>

```ad-important
title: <%tp.file.title%> Hook

***What is this campaign about? What is the goal?***

Summary:: 

```

```ad-faq
title: Six Truths of the World
***What makes this campaign unique?***
1.
2.
3.
4.
5.
6.
```

```ad-info
title: Campaign Fronts:
***What are the major moving forces in this campaign?***

---

**Front 1:**

**Goal:**

**Three Grim Portents:**

---

**Front 2:**

**Goal:**

**Three Grim Portents:**

---

**Front 3:**

**Goal:**

**Three Grim Portents:**
```

```ad-tldr
title: Player Characters in <%tp.file.title%>
```dataview
TABLE
class AS "Character Class",
race AS "Character Race",
organization AS "Affiliation",
ddb_link AS "link:",
player AS "Player"
FROM #player-characters AND [[<%tp.file.title%>]]
```


---
````ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```
````

