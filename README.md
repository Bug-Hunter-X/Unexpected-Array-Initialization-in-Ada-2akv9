# Ada Array Initialization Bug

This repository demonstrates a subtle bug related to array initialization in Ada.  The example code shows how failing to explicitly initialize an array can lead to unexpected values being used, potentially causing program errors or incorrect results.

The `bug.ada` file contains the buggy code. The `bugSolution.ada` file provides a corrected version that addresses the potential issue.

This illustrates a common pitfall for Ada programmers who might not be aware of the default initialization behavior for array types.

## How to Reproduce

1. Compile and run `bug.ada`.
2. Observe the potentially unpredictable output due to uninitialized array elements.
3. Compile and run `bugSolution.ada` to see the corrected behavior.
