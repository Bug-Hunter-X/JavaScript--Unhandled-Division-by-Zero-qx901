# JavaScript Unhandled Division by Zero

This repository demonstrates an example of unhandled division by zero in JavaScript and shows how to properly handle it.  The `bug.js` file contains the faulty code, while `bugSolution.js` provides the corrected version.

## Bug Description
The original code lacks error handling for the `divide` function, leading to a runtime error if a zero is provided as the divisor. The improved solution gracefully handles this edge case by using a try-catch block.