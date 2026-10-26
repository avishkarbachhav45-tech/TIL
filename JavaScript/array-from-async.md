# JavaScript Array.fromAsync()

- `Array.fromAsync()` creates an array from an asynchronous iterable or iterable of values
- It awaits promises returned by the input before adding their resolved values to the array
- It is useful for converting asynchronous data sources into arrays
- It returns a Promise that resolves to the resulting array