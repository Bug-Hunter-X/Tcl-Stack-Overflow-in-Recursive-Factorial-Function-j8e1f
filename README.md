# Tcl Stack Overflow Example

This repository demonstrates a common error in Tcl: stack overflow due to unbounded recursion.  The `factorialBug.tcl` file contains a recursive factorial function that will crash for larger input values.  The `factorialSolution.tcl` file provides a corrected, iterative solution.

## How to Reproduce

1.  Clone this repository.
2.  Run `factorialBug.tcl` using a Tcl interpreter. Observe the error for larger inputs (e.g., factorial 1000). 
3. Run `factorialSolution.tcl` to see the corrected, iterative implementation.