# Class 37 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

### Multiple Reducers Example
1. Why create multiple reducers?
> Create multiple reducers to manage different parts of the application state independently, making code more modular and maintainable.
2. How would you combine multiple reducers?
> Combine multiple reducers using the `combineReducers() `utility provided by Redux.
3. How will you manage state as an immutable object? why?
> Manage state as an immutable object by returning a new state object in reducers for each state change. This ensures data consistency, easier debugging, and better predictability of application behavior.

### Redux Docs: Using Combined Reducers
1. `combineReducers` is a utility function to simplify the most common use case when writing ________.
> `Redux reducers`
2. Explain how `combineReducers` assembles the new state tree.
> `combineReducers` assembles the new state tree by calling each individual reducer with the corresponding part of the state and combining their results into a single state object.
3. How would you define initial state in an app using `combineReducers`?
> You can define initial state in an app using combineReducers by providing it as the default value in the reducer functions.

### Redux Doc: Combined Reducer Syntax
1. Why will you want to split your reducing functions as your app becomes more complex?
> As an app becomes more complex, splitting reducing functions is helpful to maintain code organization and avoid one large, monolithic reducer.
2. The ________ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ________.
> 1. `combineReducers `
> 2. ` Redux store`
3. What is a popular convention when naming reducers?
> A popular convention when naming reducers is to name them after the part of the state they manage, e.g., todosReducer for managing the "todos" part of the state.

### Things I want to learn more about.

#### I utilized ChatGPT to help with some of the answers