# Class 36 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

### Application State with Redux
1. What is the first principle of Redux?
> The first principle of Redux is that the entire application state is stored in a single immutable object, often referred to as the "state tree."
2. What is a store and what do we use our reducers for within that store?
> A store in Redux is an object that holds the application state. Reducers are used within the store to specify how the state should change in response to actions.
3. Name three Redux store methods given to us by createStore and describe their use.
> 1.  `getState()` - to retrieve the current state
> 2.  `dispatch(action)` - to dispatch actions that trigger state changes
> 3. `subscribe(listener)` - to register callback functions for state changes
4. Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.
> `combineReducers()` in Redux is a utility function that combines multiple reducer functions into a single reducer. It's useful because it simplifies the management of different parts of the application state and makes the code more organized, helping with modularity and maintainability.

### Things I want to learn more about.

#### I utilized ChatGPT to help with some of the answers