# Class 32 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because utilizing both reducer and context offers clean and efficient way to manage state.

### Scaling Up with Reducer and Context
1. How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)
> `useReducer` and `useContext` are two crucial hooks in React that collaborate to simplify state management, enabling any component to read and update state above it. This powerful combination involves creating two contexts, one for state and another for dispatch functions. These contexts are then provided from the component that uses the reducer, allowing components below to access and interact with them. By following this pattern, you can effectively centralize your state management, reducing the need for prop drilling and promoting cleaner and more maintainable code.
> 
> To further streamline your components and enhance organization, you can move all the wiring into a single file. For instance, you can export a component like `TasksProvider` that provides the necessary context, and also export custom hooks like `useTasks` and `useTasksDispatch` to read it. This modular approach enables you to have multiple context-reducer pairs in your app, each encapsulating its own state and actions, making your application more scalable and maintainable.

### Things I want to learn more about.
> I want to implement useContext with useReducer and see how this relationship works.

#### I utilized ChatGPT to help with some of the answers