# Optimistic Locking

- Optimistic locking assumes that multiple users can read the same data without conflicts most of the time
- Before updating data, the application checks whether the record has changed since it was read
- A version number or timestamp is commonly used to detect conflicting updates
- If a conflict is detected, the update can be rejected and retried with the latest data