# Database Read Replicas

- Read replicas are copies of a primary database used mainly for read operations
- Write operations are handled by the primary database and changes are replicated to the replicas
- Read replicas can distribute read traffic and reduce the load on the primary database
- They are useful for applications with a high number of database read requests