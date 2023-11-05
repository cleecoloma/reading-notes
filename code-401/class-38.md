# Class 38 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

### async actions
1. Why use Redux middleware?
> Use Redux middleware to intercept and handle actions before they reach the reducer, enabling tasks like logging, side effects, and asynchronous operations.
2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
> In the Redux Async Data Flow, actions trigger the middleware, which can handle asynchronous tasks and then dispatch new actions when complete. Reducers process these actions to update the state.
3. How are we accommodating async in our Redux app?
> We accommodate async in our Redux app by using middleware like Redux Thunk to dispatch asynchronous actions, allowing us to fetch data or perform other async operations before updating the state.

### thunk middleware
1. Why would you need redux-thunk middleware?
> Redux Thunk middleware is needed to handle asynchronous actions in Redux.
2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
> `function`
3. Describe how any return value from the inner thunk function will be made available.
> The return value from the inner thunk function will be made available for further processing by Redux, such as updating the state, after the asynchronous operation is complete.

### Things I want to learn more about.

#### I utilized ChatGPT to help with some of the answers