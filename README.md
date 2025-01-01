# Hoisting Bug in Javascript

This repository demonstrates a common error in JavaScript related to hoisting.  The `bug.js` file contains code that exhibits unexpected behavior due to hoisting. The `bugSolution.js` file shows how to correctly structure the code to avoid this problem.

## Bug Description

JavaScript's hoisting mechanism moves variable declarations to the top of their scope. However, it only hoists declarations; it does not hoist initializations.  This can lead to unexpected `undefined` values if you try to use a variable before it is assigned a value.  The example in `bug.js` demonstrates this problem.