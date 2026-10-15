# Kubernetes Liveness and Readiness Probes

- Liveness probes check whether a container is still running properly
- Readiness probes determine whether a container is ready to receive traffic
- Kubernetes can restart a container when its liveness probe repeatedly fails
- Readiness probes help prevent traffic from reaching an application that is not ready