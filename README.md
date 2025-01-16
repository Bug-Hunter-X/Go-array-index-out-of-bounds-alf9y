# Go Array Index Out of Bounds Error

This repository demonstrates a common error in Go: an array index out of bounds error.  The error arises when attempting to access an array element using an index that is outside the valid range of the array. 

In the `bug.go` file, a for loop iterates beyond the valid index range of the array, causing a runtime panic.  The solution (`bugSolution.go`) addresses this issue by correctly limiting the loop iteration to stay within the array's bounds.