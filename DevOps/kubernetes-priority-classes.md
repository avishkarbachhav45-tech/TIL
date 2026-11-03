# Kubernetes Priority Classes

- A PriorityClass assigns a priority value to pods in a Kubernetes cluster.
- Higher-priority pods can be scheduled before lower-priority pods when resources are limited.
- Priority classes help Kubernetes decide which pods to schedule or evict during resource pressure.
- The `priorityClassName` field connects a pod to a defined PriorityClass.