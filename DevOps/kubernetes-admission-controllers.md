# Kubernetes Admission Controllers

- Admission Controllers intercept requests to the Kubernetes API server after authentication and authorization.
- They validate or modify requests before the API server persists them.
- Mutating admission controllers can modify resource configurations.
- Validating admission controllers check requests against rules and can reject invalid configurations.