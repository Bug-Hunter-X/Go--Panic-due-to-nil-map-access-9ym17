# Go: Panic due to nil map access

This repository demonstrates a common error in Go: accessing a map literal without checking for nil.  Attempting to assign a value to an uninitialized map will cause a runtime panic.

The `bug.go` file shows the problematic code, while `bugSolution.go` provides a corrected version.  Always check if a map is nil before accessing its elements to avoid unexpected crashes.