# Linux fstrim

- `fstrim` discards unused blocks on supported storage devices and filesystems
- It helps SSDs and thin-provisioned storage identify blocks that are no longer in use
- `sudo fstrim -v /` runs trim on the filesystem mounted at the root directory
- Regular trimming can help maintain SSD performance and efficient storage management