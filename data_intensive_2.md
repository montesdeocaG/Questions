
## Chapter 2



**1. Define impendance mismatch**

Its an object-relational conceptual difficulty, it happens whem a RBDS is being served by an application that is written in OOP, this is because objects/classes must be mapped to database tables defined by a relational schema.


**2. Mention the advantages of using document models**
Benefits of using them are schema flexibility, a better performance due to their local usage, appropiate for OOP languages.


**3. Normalized DB vs Denormalized DB.**
A normalized DB utilizes ID to refer to its entities, a denormalized DB instead will duplicate properties of the entities.


**4. Name 5 graph databases and characteristics** 
ArangoDB: A native multi-model database, ACID, HTTP API, doc key/value and graph models are supported
AzureCosmos: multi-model db system, multi-languge API, ellastic and independant scaling.
Neo4J: A native multi-model db, flexible, high avaibility
Amazon Neptune: High-performance low latency and high scability, security.
OrientDB: Unified model API, easy RDBS migration, written in java.


**5. Distribuited file system vs relational file system**

Relational supports the SQL like operations, distribuited simply do key-value stores.  when it comes to one-to-many databases the relational DBS win, however with many-to-many complex relationships then we should use distribuited since our model looks like a graph.


**6. Describe graph properties**
A graph has two objects, vertikces and edges, the vertices are the nodes and the edges will be representations of the relationships.
Every vertex has a unique ID and a set of out and incoming edges. Every edge has a unique ID, tail and head and a label.



```

```
