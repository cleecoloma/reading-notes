# Class 27 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because hooks are relevant while utilizing React.

### Thinking in React
1. Summarize the five steps of thinking in react.
> 1. **Break the UI into a component hierarchy** - you break down the user interface into a component hierarchy by identifying and naming components based on the design, considering principles like the single responsibility principle, and mapping the UI to the data model.
> 
> 2. **Build a static version in React** - After creating the component hierarchy, you proceed to implement your app by building a static version. The static version doesn't include interactivity and is designed to render the UI based on the data model.
>
> 3. **Find the minimal but complete representation of UI state** - You aim to make the UI interactive by allowing users to modify your underlying data model, which is accomplished through the use of state. State represents the minimal set of changing data that your app must remember, adhering to the DRY (Don't Repeat Yourself) principle.
> 
> 4. **Identify where your state should live** - You identify which component is responsible for changing the state or "owns" the state. This step is crucial for enabling interactivity in your application.
>
> 5. **Add inverse data flow** - You enable data flow in the opposite direction, allowing form components deep within the component hierarchy to update the state in the top-level component, which is FilterableProductTable in this example. This step involves passing functions as props to child components to handle user input and update the state. 

### State: A Component's Memory
1. What is one reason a local variable isn’t sufficient for managing a React component?
> Local variables don’t persist between renders.
2. What is the argument to the useState hook, and what are the two parts of its return array?
> The argument in a useState hook is the initial state value. The first element inside the return array is the current state value. The second element inside the return array is a function that updates the state.
3. How can Component A access state from Component B?
> By using props that is passed down from parent component to the child component.

### Additional Questions
1. What are your learning goals after reading and reviewing the class README?
> I want to learn more about my first React hook.

### Things I want to learn more about.
> See Additional Questions above.

#### I utilized ChatGPT to help with some of the answers
