# Linux lsof

- `lsof` stands for List Open Files and shows files and resources currently opened by processes
- It can be used to identify which process is using a specific file
- It can also help find processes using a particular network port
- `lsof -i :8080` can be used to check which process is using port 8080