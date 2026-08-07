# Idempotency

- An idempotent operation produces the same result even if it is executed multiple times
- HTTP methods such as GET, PUT, and DELETE are idempotent, while POST is generally not
- Idempotency keys help prevent duplicate requests in payment and order processing systems