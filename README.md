# Ada Primality Test Bug

This repository demonstrates a common, yet subtle, error in a simple Ada program designed to check if a number is prime. The `bug.ada` file contains the erroneous code. The error is related to the handling of small prime numbers and the loop termination condition. The `bugSolution.ada` file provides a corrected and more efficient version.

## How to Reproduce

1. Compile `bug.ada`.
2. Run the compiled program. Test with various inputs, including small prime numbers like 2, 3, 5 etc., and notice the incorrect results for some inputs.
3. Compile and run `bugSolution.ada` to see the correct results.

## Learning Points

This bug highlights the importance of:
* Carefully considering edge cases and boundary conditions when writing algorithms.
* Choosing efficient algorithms for common tasks. The original code contains unnecessary checks.
* Thoroughly testing code with various inputs to uncover hidden issues. 