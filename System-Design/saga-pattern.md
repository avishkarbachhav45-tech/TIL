# Saga Pattern

- Saga Pattern manages distributed transactions by dividing them into smaller local transactions
- Each local transaction updates its own service and triggers the next step
- If a step fails, compensating actions are used to undo previously completed operations
- It is useful in microservices where a single database transaction cannot span multiple services