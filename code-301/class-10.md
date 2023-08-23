# Class 10 Summary
## Code 301 - Intermediate Software Development

> These topics relates because...

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
2. What is a ‘syntax error’?
3. What is a ‘range error’?
4. What is a ‘type error’?
5. What is a breakpoint?
6. What does the word ‘debugger’ do in your code?

### Things I want to learn more about.
> None


###### I also utilized ChatGPT with some of the questions.