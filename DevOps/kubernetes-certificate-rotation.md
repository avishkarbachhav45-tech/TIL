# Kubernetes Certificate Rotation

- Kubernetes uses TLS certificates to secure communication between cluster components.
- Certificates have an expiration date and must be renewed before they expire.
- Kubelet can automatically rotate its client certificates when certificate rotation is enabled.
- Regular certificate rotation helps maintain secure communication and prevents authentication failures.