---
title: Witness - Name or Role
tags: [witness]
type: witness
---

## Witness profile

name:: 
role:: 
training_or_credentials:: 
service_or_organization:: 
credibility_assessment:: 

## Encounters witnessed

```dataview
LIST
FROM "02 - Incidents"
WHERE contains(witnesses, this.file.link)
SORT date_event DESC
```

## Notes

Background, training relevant to identification of aerial objects, any pre-existing biases or motivations to consider.
