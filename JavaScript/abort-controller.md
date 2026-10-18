# JavaScript AbortController

- AbortController allows us to cancel asynchronous operations such as fetch requests
- It provides an AbortSignal that communicates when an operation should be cancelled
- The signal can be passed to fetch using the `signal` option
- It is useful for cancelling outdated API requests and preventing unnecessary network operations