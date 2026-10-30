# Kubernetes Init Containers

- Init Containers are specialized containers that run before the main application containers in a Pod
- They execute tasks such as configuration setup, dependency checks, and database preparation
- Kubernetes starts application containers only after all Init Containers complete successfully
- If an Init Container fails, Kubernetes retries it according to the Pod's restart policy