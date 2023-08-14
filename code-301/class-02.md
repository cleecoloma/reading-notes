# Class 02 Summary
## Code 301 - Intermediate Software Development

> These topics relates because React lifecycle, state, and props will be a big part in handling the front-end side of any web application.

### React Lifecycle
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
> `render` will run first before `componentDidMount`.
2. What is the very first thing to happen in the lifecycle of React?
> The very first thing that happens in a React lifecycles is Mounting. This is when an instance of a component is being created and inserted into DOM.
3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
> 1. `constructor`
> 2. `render`
> 3. `componentDidMount`
> 4. `React Updates`
> 5. `componentWillUnmount`
4. What does `componentDidMount` do?
> `componentDidMount` allows you to perform side effects, such as data fetching or setting up subscriptions.

### React State vs Props
1. What types of things can you pass in the props?
> Data and functions are things that can be passed in the props.
2. What is the big difference between props and state?
> Props are handled/updated outside of the React components while state is handled/updated inside the React component.
3. When do we re-render our application?
> Re-render happens in our application when there is a change in either the props or state.
4. What are some examples of things that we could store in state?
> * Form input values and their validation results
> * API data fetched asynchronously
> * Toggle states for showing/hiding elements
> * Counters or numerical values that change based on user interactions
> * User authentication status

### Things I want to learn more about.
> I want to learn more about React state and how I can apply on on course and personal projects.


###### I utilized ChatGPT to answer some of these questions.