# Class 10 Summary
## Code 301 - Intermediate Software Development

> These topics relates because errors are a big part in programming. I always get errors and most of the time it is hard to debug them.

### Understanding the JavaScript Call Stack
1. What is a ‘call’?
> 'Call' is a function invocation.
2. How many ‘calls’ can happen at once?
> One at a time.
3. What does LIFO mean?
> LIFO stands for Last In, First Out. It means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
```javascript
function secondFunction() {
    console.log("Inside secondFunction");
}
function firstFunction() {
    secondFunction();
    console.log("Inside firstFunction");
}
function main() {
    firstFunction();
    console.log("Inside main");
}
main();
```
> In this example:
> 1. The `main` function is called.
> 2. Inside the `main` function, the `firstFunction` is called.
> 3. Inside the `firstFunction`, the `secondFunction` is called.
> 4. The `secondFunction` doesn't have any more function calls, so it completes and is removed from the stack.
> 5. The `firstFunction` completes its execution and is removed from the stack.
> 6. The `main` function continues executing.
> 7. The `main` function completes and is removed from the stack.
5. What causes a Stack Overflow?
> Stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

### JavaScript error messages
1. What is a ‘reference error’?
> A 'reference error' is an error that occurs when a variable is used that has not been declared.>
2. What is a ‘syntax error’?
> A 'syntax error' is an error that occurs when the code does not follow the correct syntax rules.
3. What is a ‘range error’?
> A 'range error' is an error that occurs when a value is outside of the allowed range for a variable.
4. What is a ‘type error’?
> A 'type error' is an error that occurs when a value is assigned to a variable of the wrong type.
5. What is a breakpoint?
> A breakpoint is a point in your code where the execution will stop so you can inspect the values of variables and the call stack.
6. What does the word ‘debugger’ do in your code?
> The word 'debugger' is used to start the debugger in your code.

### Things I want to learn more about.
> None


###### I also utilized Bard with some of the questions.