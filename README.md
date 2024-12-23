# Uncommon HTML Error: Unexpected innerHTML behavior
This repository demonstrates an uncommon error related to the use of innerHTML in HTML/JavaScript.  The error arises from attempting to assign a numeric value directly to innerHTML, which expects a string.  The solution illustrates the correct approach.

## Bug
The `bug.html` file demonstrates the incorrect usage of innerHTML with a number.

## Solution
The `bugSolution.html` file provides the corrected code that converts the number to a string before assignment to innerHTML.