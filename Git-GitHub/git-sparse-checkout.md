# Git Sparse Checkout

- Git Sparse Checkout allows us to checkout only selected files or directories from a repository
- It is useful when working with large repositories where the entire project is not needed locally
- It reduces the amount of files stored in the working directory
- It can be enabled using `git sparse-checkout init` and configured with `git sparse-checkout set`