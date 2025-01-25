# Unhandled Non-Numeric Input in JavaScript Arithmetic Functions

This repository demonstrates a common error in JavaScript: the lack of error handling for non-numeric input in arithmetic functions. The `bug.js` file contains the initial code with the potential bug.  `bugSolution.js` provides an improved version with error handling.

The bug arises when functions like `add` and `subtract` receive non-numeric arguments. This leads to unexpected results due to JavaScript's type coercion.  The solution introduces checks to ensure inputs are numbers, providing more robust and predictable function behavior. 