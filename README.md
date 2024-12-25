# Uncommon HTML Error: Incorrect Accessing of HTML Elements using Javascript
This repository demonstrates a subtle error that can occur when accessing HTML elements using Javascript's `document.getElementById` method.

The error lies in how the `id` is passed to the function.  Forgetting quotes around the `id` results in a runtime error.

## Bug
The `bug.html` file contains the incorrect code that demonstrates this error.  The script tries to access an element using the id `myDiv` but without using quotes around the ID which will cause the script to fail. 

## Solution
The `bugSolution.html` file provides the corrected code. The solution is simple: ensure the ID is passed as a string.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser. Observe the error in the browser's console.
3. Open `bugSolution.html`. The code should run without error.