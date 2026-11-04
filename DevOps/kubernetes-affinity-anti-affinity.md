# Kubernetes Affinity and Anti-Affinity

- Affinity rules influence where Kubernetes schedules pods within a cluster.
- Pod affinity can place pods near other pods that match specific labels.
- Pod anti-affinity can keep matching pods apart, improving availability and reducing concentration.
- These rules use label selectors and topology keys to define placement preferences or requirements.