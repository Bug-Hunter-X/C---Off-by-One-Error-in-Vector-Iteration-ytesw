# C++ Off-by-One Error in Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs when the loop condition incorrectly includes the element at the `vec.size()` index, which is one past the last valid element.

The `bug.cpp` file contains the erroneous code, and `bugSolution.cpp` provides the corrected version.

This is a simple example, but similar errors can occur in more complex scenarios and can be difficult to debug.