# Kubernetes Topology Spread Constraints

- Topology Spread Constraints distribute pods evenly across nodes or availability zones.
- They help prevent workloads from being concentrated in a single failure domain.
- The `topologyKey` field defines the topology domain, such as a node or zone.
- `maxSkew` controls the maximum permitted difference in pod distribution between domains.