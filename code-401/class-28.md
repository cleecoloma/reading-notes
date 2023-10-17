# Class 28 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because 

### useEffect Hook
1. What is the main intended use case for the useEffect hook?
> `useEffect` is a React Hook that lets you synchronize a component with an external system.
2. How does the effect’s logic interact with the component?
> The effect's logic is defined within the useEffect function as a callback. It runs after the component has rendered and can interact with the component's state, props, and other data, allowing you to update the component in response to changes in these values.
3. What is the importance of the return value from the effect’s logic function?
> The return value from the effect's logic function is essential for cleanup and avoiding memory leaks. It typically includes code to cancel subscriptions, remove event listeners, or perform other cleanup tasks, ensuring that no unintended side effects or resource leaks occur when the component is unmounted or the effect's dependencies change.

### Additional Questions
1. What are your learning goals after reading and reviewing the class README?
> I want to learn more about utilizing useEffect and chat applications together.

### Things I want to learn more about.
> See Additional Questions above.

#### I utilized ChatGPT to help with some of the answers