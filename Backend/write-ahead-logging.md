# Write-Ahead Logging (WAL)

- Write-Ahead Logging records changes in a log before applying them to the database
- It helps databases recover data after crashes or unexpected shutdowns
- The log can be used to replay changes that were not fully written to the database
- WAL improves database reliability and supports transaction durability