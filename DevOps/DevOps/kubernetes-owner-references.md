# Kubernetes Owner References

- Owner References establish ownership relationships between Kubernetes resources.
- They help Kubernetes identify dependent resources associated with an owner object.
- When an owner is deleted, garbage collection can automatically remove its dependent resources.
- The `ownerReferences` field in resource metadata stores information about the owner object.