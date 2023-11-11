# Class-39 Reading Notes

## Redux Toolkit (RTK)

> 1. ***What concerns are addressed by Redux Toolkit?***
> Redux Toolkit is a collection of utility functions, configurations, and recommended practices that address several concerns associated with using Redux for state management in React applications.Redux Toolkit simplifies the syntax and reduces the amount of boilerplate code required to set up a Redux store. Redux Toolkit provides a configureStore function that simplifies the store configuration process. It automatically sets up the Redux store with sensible defaults, including middleware like Redux Thunk for handling asynchronous actions.
>
> 2. ***What does configureStore() do?***
>Middleware is a way to extend the Redux store's abilities. It can be used for logging, crash reporting, asynchronous actions, etc. configureStore() allows you to add middleware to the Redux store.
>It takes one or more reducer functions as arguments. Reducers are functions that specify how the application's state changes in response to actions sent to the store.
> 3. ***How would I use createSlice()?***
>createSlice() is a function provided by the Redux Toolkit, a set of utilities and abstractions to simplify Redux development. It's used to define a slice of the Redux state along with the actions and reducer for that slice.
>

## MobX
> 1. ***What is Mobx?***
> MobX is a JavaScript library for state management. It is often used in conjunction with React, but it can be used with any JavaScript framework or library. MobX provides a simple and scalable state management solution, focusing on making state management easy and efficient.
>
> 2. ***How does MobX make it “impossible” to produce an inconsistent state?***
>MobX achieves a high level of consistency in state management by adhering to a set of principles and leveraging its reactive programming model. In MobX, state is marked as observable, which means that any part of the application that relies on this state is automatically notified when it changes. This eliminates the need for manual tracking of state changes and helps in avoiding inconsistencies.
>
> 3. ***How would we build a reactive user interface?***
>
Building a reactive user interface involves creating an interface that updates automatically in response to changes in the underlying data or state. Define a MobX store to manage the state of your application. MobX allows you to create observable state and actions to modify that state. Build a React component that observes the state from the MobX store using the observer function from mobx-react. This ensures that the component re-renders whenever the observed data changes. Build a root React component that renders the reactive component and then render
>

## Things I want to know about
