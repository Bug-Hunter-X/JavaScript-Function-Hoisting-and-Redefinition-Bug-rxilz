# JavaScript Function Hoisting Bug
This repository demonstrates a subtle bug related to function hoisting in JavaScript.  When a function is redefined, the later definition overrides the earlier one. This can lead to unexpected behavior if not carefully managed.  See `bug.js` for the buggy code and `bugSolution.js` for the solution.

## Bug Description
The bug arises from redefining the `foo` function. The first definition adds two numbers, while the second subtracts them. The output depends on which definition is called. This highlights the importance of understanding how function hoisting affects code execution order.

## Solution
The solution involves either avoiding redefinition or carefully controlling the order of function calls to ensure the desired behavior. The solution (`bugSolution.js`) provides a more controlled structure to prevent such unexpected behavior.