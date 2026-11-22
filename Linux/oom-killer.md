# Linux OOM Killer

- The Out-Of-Memory (OOM) Killer is a Linux mechanism that handles situations when system memory is exhausted.
- It selects and terminates processes to free memory and prevent the system from becoming unstable.
- Processes can have their `oom_score` adjusted to influence the likelihood of being terminated.
- OOM-related events can be inspected through system logs to identify memory-related issues.