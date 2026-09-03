# Database Connection Pooling

- Connection pooling maintains a reusable set of database connections
- Applications borrow a connection from the pool when needed and return it after the operation
- Reusing connections reduces the overhead of repeatedly creating and closing database connections
- Pool size should be configured carefully to avoid exhausting database resources