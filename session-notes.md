---
alias: "Week of <% moment().isoWeekday(7).format("Do MMMM YYYY") %>"
type: "session-notes"
tags:
  - "dnd" 
  - "session-notes"
date_created: <% tp.file.creation_date("YYYY-MM-DD")%>
dnd_session_date: 
summary: [""]
---
# Session Notes: <% moment().isoWeekday(7).format("MMMM Do YYYY") %>
#session-notes 
```ad-example
title: Log
collapse: open

#### Players:: ""
#### **Campaign**:: 
#### Starting_Location::
#### Music::
```


## Review the Characters

## Create a Strong Start

## Outline Potential Scenes

## Define Secrets and Clues

## Develop Fantastic Locations

## Outline Important NPCs
1. - 
2. -
3. -
## Choose relevant monsters

## Select magic item rewards

<% await tp.file.move("/dnd/session-notes/" + moment().isoWeekday(7).format("YYYY-MM-DD") + " Session Notes") %>