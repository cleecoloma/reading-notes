# Class 21 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because learning more React hooks is a good thing.

### Choosing the State Structure
1. Summarize the five principles for structuring state.
  * ***Group related state:*** Combine state variables updated together into one.
  * **Avoid contradictions in state:** Prevent conflicting state information.
  * ***Avoid redundant state:*** Don't store data that can be calculated from props or existing state.
  * ***Avoid duplication in state:*** Reduce repeated data within state.
  * ***Avoid deeply nested state:*** Keep state hierarchy flat for easier updates.

### Passing State Deeply with Context
1. What problem do Contexts aim to solve?
  > Passing props can become verbose and inconvenient when you need to pass some prop deeply through the tree, or if many components need the same prop. React's context feature allows to “teleport” data to the components in the tree that need it without passing props
2. What is one technique to try before useContext?
> Prop drilling method - passing props down the component tree from parent to child
3. What hook complements useContext for complex applications?
> useReducer complements useContext.

### Things I want to learn more about.
> I want to implement useContext with useReducer and see how this relationship works.

#### I utilized ChatGPT to help with some of the answers