---
topic: cqrs
display_name: Command Query Responsibility Segregation (CQRS)
short_description: Command Query Responsibility Segregation (CQRS) is a system architecture design pattern as an alternative to CRUD.
created_by: Greg Young, Udi Dahan
released: February 16, 2010
related: cqs, ddd, crud, event-sourcing
url: http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/
wikipedia_url: https://en.wikipedia.org/wiki/Command_Query_Responsibility_Segregation
---
**Command Query Responsibility Segregation** (**CQRS**) is a system architecture design pattern as an alternative to [CRUD](/topics/cruid) that extends the idea behind [command–query separation](/topics/cqs) to the level of services. The change that CQRS introduces is to split that conceptual model into separate models for update and display, which it refers to as Command and Query respectively following the vocabulary of CommandQuerySeparation. The rationale is that for many problems, particularly in more complicated domains, having the same conceptual model for commands and queries leads to a more complex model that does neither well. The models used to process queries are usually called "read models" and the models used to process commands "write models". 
