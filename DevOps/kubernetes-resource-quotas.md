# Kubernetes Resource Quotas

- A ResourceQuota limits the total amount of resources that can be consumed within a namespace.
- It can control CPU, memory, storage, and the number of Kubernetes objects.
- Resource quotas help prevent one team or application from consuming all cluster resources.
- Kubernetes rejects requests that exceed the quota until resources become available or the quota is changed.