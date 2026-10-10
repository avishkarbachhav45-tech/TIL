# JavaScript WeakMap

- WeakMap stores key-value pairs where keys must be objects or non-registered symbols
- It allows objects used as keys to be garbage-collected when no longer referenced elsewhere
- WeakMap keys are not enumerable, so methods like `keys()` and `entries()` are unavailable
- It is useful for associating private or additional data with objects without preventing their garbage collection