# Uncommon JavaScript Bug: Hoisting and Unexpected Behavior

This repository demonstrates a subtle bug in JavaScript related to hoisting and variable declarations.

## The Bug

The code in `bug.js` illustrates a scenario where a variable is used before it's declared.  Due to JavaScript's hoisting mechanism, the variable declaration is moved to the top of its scope, but the initialization is not. This leads to the variable being `undefined` when it is first accessed, causing unexpected behavior.

## The Solution

The solution in `bugSolution.js` fixes the bug by ensuring that the variable is declared and initialized before it's used. This avoids the undefined value and produces the expected output.

## How to reproduce

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js`.
3. Execute both files separately in a JavaScript environment (browser console or Node.js).
4. Observe the difference in output.