# Class-30 Reading Notes

## Choosing the State Structure

> 1. ***Summarize the five principles for structuring state.***
> 1. Single Source of Truth:
Principle: The state of your whole application should be stored in a single JavaScript object.
Explanation: Having a centralized state management makes it easier to manage and update the state consistently. It ensures that there's only one way to change the state, making the application behavior more predictable and debuggable.
2. State is Read-Only:
Principle: The state cannot be directly modified. To change the state, you dispatch actions.
Explanation: State should be treated as immutable. Components cannot directly alter the state; instead, they trigger actions, which are then processed by reducers to create a new state. This immutability simplifies tracking changes and understanding when and why state updates occur.
3. Changes are Made with Pure Functions:
Principle: To specify how the state tree is transformed by actions, you write pure reducers.
Explanation: Reducers are pure functions that specify how the application's state changes in response to actions. They take the previous state and an action, and return a new state without modifying the previous state. This predictability ensures that given the same input, a reducer will always produce the same output.
4. Action Types Should be Constants:
Principle: Represent each action type as a constant to avoid typos and ensure consistency.
Explanation: Action types (strings describing the type of action being performed) are often stored as constants. This practice helps prevent typos, ensures consistency throughout the application, and makes it easier to refactor code without introducing bugs.
5. State Changes are Described as Plain Objects:
Principle: Actions are plain JavaScript objects that have a type property and additional payload properties.
Explanation: Actions are simple objects that describe what happened in the application. The type property defines the type of action being performed, and additional properties (payload) contain any necessary data for the action. Following this convention keeps actions straightforward and easy to understand.
>

## Passing State Deeply with Context

> 1. ***What problem do Contexts aim to solve?***
> Complex Prop Chains: As your application grows, passing props through multiple levels becomes cumbersome and results in complex and hard-to-read code.

Component Coupling: Components in the middle of the hierarchy end up being tightly coupled to the structure of the data even if they don't directly use it. This reduces component reusability.

Maintenance Challenges: If the structure of the data changes, you have to update the props in multiple places, which can lead to maintenance challenges and potential errors.

Reduced Readability: Code readability suffers as developers need to trace prop chains to understand how data is being passed through the components.
>
> 2. ***What is one technique to try before useContext?***
> Before using the useContext hook in React, one technique to manage global state or shared data across components is using prop drilling.

In prop drilling, you pass down props from a higher-level component to one or more levels of nested child components. While it can lead to complex prop chains, it's a straightforward and built-in way to share state between components in React.
>
> 3. ***What hook complements useContext for complex applications?***
> In complex applications where state management requirements become more sophisticated, the useReducer hook is often used in conjunction with useContext to complement the state management capabilities provided by the Context API.

useReducer is a React hook that is an alternative to useState. While useState is useful for managing individual pieces of state, useReducer is beneficial when you have complex state logic that involves multiple actions, especially in cases where state transitions depend on the previous state.
>

## Things I want to know about
