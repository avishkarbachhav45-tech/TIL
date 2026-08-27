# ETag

- ETag is an HTTP response header used to identify a specific version of a resource
- The client can send the ETag back using the If-None-Match header
- If the resource has not changed, the server can return 304 Not Modified instead of sending the full response
- ETags reduce unnecessary data transfer and improve caching efficiency 