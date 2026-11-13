# Kubernetes Finalizers

- Finalizers are keys in Kubernetes resource metadata that control when an object can be deleted.
- When deletion is requested, Kubernetes sets a deletion timestamp but keeps the object until its finalizers are removed.
- Controllers perform cleanup tasks before removing their finalizer.
- Once all finalizers are removed, Kubernetes completes the deletion of the resource.