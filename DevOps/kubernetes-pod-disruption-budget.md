# Kubernetes Pod Disruption Budget

- A Pod Disruption Budget (PDB) limits how many pods can be unavailable during voluntary disruptions.
- It helps maintain application availability during node maintenance or cluster upgrades.
- `minAvailable` specifies the minimum number of pods that must remain available.
- `maxUnavailable` specifies the maximum number of pods that can be unavailable at once.