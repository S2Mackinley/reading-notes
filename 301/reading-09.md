# reading 09

a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

`function firstFunction(){`

`throw new Error('Stack Trace Error');`

`}`

`function secondFunction(){`

`firstFunction();`

`}`

`function thirdFunction(){`

`secondFunction();`

`}`

`thirdFunction();`

When the code is ran the stack is printed out with each error stacked on each other in order.
