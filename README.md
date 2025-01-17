
# mathutil

## Directory Structure
```plaintext
mathutil/
├── go.mod
├── go.sum
└── mathutil
    ├── addition.go
    ├── subtraction.go
    └── multiplication.go
```

## Why `mathutil` Doesn't Have a `main` Function

### Purpose

The `mathutil` package is designed solely to provide reusable functions for mathematical operations. It's intended to be imported and used by other programs or packages.

### Modularity

By separating utility functions into a package (`mathutil`), we can promote code modularity and reusability. Other programs or packages can import `mathutil` to perform mathematical operations without needing to redefine those operations.

### No Entry Point

Since `mathutil` is not an executable program but rather a collection of functions, it does not require a `main` function. In Go, only executable programs (those with a `main` function) have an entry point.

## Create a Module

```bash
PS C:\Users\AV******\Go practice_1107\mathutil> go mod init github.com/shaileshyadav7771/mathutil
go: creating new go.mod: module github.com/shaileshyadav7771/mathutil
go: to add module requirements and sums:
        go mod tidy
PS C:\Users\AV********\Go practice_1107\mathutil>
```
