# ![connectivity32](https://user-images.githubusercontent.com/10895608/83115619-fda02880-a10d-11ea-88ba-a9186eb8d517.png) FactEngine

![FactEngine-5-Venn2](https://user-images.githubusercontent.com/10895608/83111640-47861000-a108-11ea-950c-46b27df4d3d3.jpg)

FactEngine is a knowledge graph for knowledge engineering and querying.

FactEngine combines a powerful ontology/semantic modeling language, Object-Role Modeling, with underlying database technology to achieve a Knowledge Graph over which expressive queries can be performed to glean information from the knowledge graph.

## Knowledge Engineering with Object-Role Modeling

The thesis is simple, with a metamodel of Object-Role Modeling, a database can be viewed and queried as a graph, hierarchical or relational database.

Use our powerful Knowledge Query Language (KQL) to query over the knowledge graph or even use SQL, the choice is yours.

The technology is transposable accross any relational or key/value database. We use SQLite in this iteration because it is the most widely used database in the world and because it allows you to have a knowledge graph, graph database and relational database on your desktop and embedded into your application.

## Project Status

- We are in the early stages of creating the DLL (direct link library) for FactEngine.  
- The Boston Object-Role Modeling softwware used to create the Object-Role Model over your database/s is complete, we just need to extend the software to generate and maintain the associated SQLite database for the appropriate Models in Boston.  
- SQLite is the most widely used database in the world. It is ready to go. FactEngine operates over the top of one or more SQLite databases.



