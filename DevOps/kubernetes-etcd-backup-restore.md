# Kubernetes etcd Backup and Restore

- etcd stores Kubernetes cluster state, including configuration and resource information.
- Regular etcd backups help recover cluster data after failures or accidental changes.
- The `etcdctl snapshot save` command creates a backup of the etcd database.
- The `etcdctl snapshot restore` command restores cluster data from a saved snapshot.