# Fact Engine

Fact Engine is a <br />
     - Graph Database; <br />
     - Relational Database; <br />
     - Hierarchical Database; <br />
     - Knowledge Graph Database; <br />
     - Multi-Model Database; <br />

Fact Engine combines a powerful ontology/semantic modeling language, Object-Role Modeling, with underlying database technology to achieve a Knowledge Graph Database over which expressive queries can be performed to glean information from the knowledge graph.

The thesis is simple, with a metamodel of Object-Role Modeling, a relational database can be viewed and queried as a graph, hierarchical database...and, of course, with SQL.

Fact Engine turns a SQLite database into a graph database, knowledge graph database while preserving all the virtues of a relational database.

The technology is transposable accross any relational database. We use SQLite because it is the most widely used database in the world and because it allows you to have a knowledge graph, graph database and relational database on your desktop and embedded into your application.

## Project Status

- We are in the early stages of creating the DLL (direct link library) for FactEngine.  
- The Boston Object-Role Modeling softwware used to create the Object-Role Model over your database/s is complete, we just need to extend the software to generate and maintain the associated SQLite database for the appropriate Models in Boston.  
- SQLite is the most widely used database in the world. It is ready to go. FactEngine operates over the top of one or more SQLite databases.



