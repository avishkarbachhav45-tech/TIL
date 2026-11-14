# Kubernetes Leases

- Leases are Kubernetes API objects used to coordinate distributed processes.
- They are commonly used for leader election among Kubernetes controllers.
- A Lease contains information such as holder identity, lease duration, and renewal time.
- Nodes also use Lease objects to send heartbeats and report their availability.