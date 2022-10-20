---
date: "<%tp.date.now("YYYY-MM-DD")%>"
tags:
  - "dnd"
  - player-characters
aliases:
  - ""
ddb_link: ""
type: "player-characters"
---
# [[<%tp.file.title%>]]
<% await tp.file.move("/dnd/player-characters/" + tp.file.title) %>

#### **Summary**:: ""
#### **campaign**::
#### player:: "

## Image:


##### race: ""
##### class:
##### level: ""
##### gender: ""
##### organizations:

> [!abstract] Goal Card
> > [!question]+ Goal:
> > This is a goal
> 
>>[!done]+ Reward
>>This is a reward
>  
> 


---
````ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[<%tp.file.title%>]]
```
````