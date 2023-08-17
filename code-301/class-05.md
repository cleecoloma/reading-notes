# Class 05 Summary
## Code 301 - Intermediate Software Development

> These topics relates because understanding the best flow when creating in React application is important.

### React Docs - Thinking in React
1. What is the `single responsibility principle` and how does it apply to components?
> `Single responsibility principle` is a component that only does one thing.
2. What does it mean to build a ‘static’ version of your application?
> Building a 'static' version of the application means creating the UI first without the interactivity.
3. Once you have a static application, what do you need to add?
> Adding state for each components.
4. What are the three questions you can ask to determine if something is state?
> 1. Does it remain unchanged over time? If so, it isn’t state.
> 2. Is it passed in from a parent via props? If so, it isn’t state.
> 3. Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!
5. How can you identify where state needs to live?
> Direct common parent of the component.

### Higher-Order Functions
1. What is a “higher-order function”?
> A higher-order function is a function that takes a function as an argument and/or returns a function.
2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?
```javascript
function greaterThan(n) {
  return m => m > n;
}
```
> In line 2 above, the function is returning a function that takes `m` as an parameter.
3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.
> * `Map` - applies function to each element in an array that returns a new array with those new elements.
> * `Reduce` - takes in a callback function as a parameter which iterates through each element using that callback function.

### Things I want to learn more about.
> None.


###### I also utilized ChatGPT with some of the questions.