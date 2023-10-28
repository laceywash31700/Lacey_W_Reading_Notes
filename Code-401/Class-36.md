# Class-36 Reading Notes

## Dan Abramov Redux Tutorials

> 1. ***What is the first principle of Redux?***
>  The first principle of Redux is that the entire state of an application is stored in a single JavaScript object. This means that all the data that represents the state of your app is stored in one centralized location.
>
> 2. ***what is a store and what do we use our reducers for within that store?***
> A store in Redux is an object that holds the application state tree. It is the single source of truth for the application state. The state within a Redux store is read-only, which means the only way to change the state is to emit an action. 
>
> 3. ***Name three Redux store methods given to us by createStore and describe their use.***
> The **getState()** method is used to retrieve the current state of the Redux store. It returns the current state object, allowing you to access the current data stored in your application. This method does not take any parameter
---------------------
The **dispatch(action)** method is used to dispatch actions to the Redux store. When you dispatch an action, it triggers the execution of the reducer function associated with the store. The reducer then specifies how the state should change based on the action type.
---------------------
The **subscribe(listener)** method allows you to register a callback function (listener) that will be called whenever an action is dispatched and the state of the store potentially changes. It sets up a subscription to the store, and the provided listener will be called every time an action is dispatched.
>
> 4. ***Explain to a non-technical recruiter what combineReducers() does and why it is useful***
>   Your application's data is like a big puzzle, broken down into smaller pieces.
combineReducers() helps organize these pieces by assigning each piece to a specific team (or a Redux reducer in technical terms).
>  combineReducers() brings order to the puzzle-solving process. It ensures that every team knows which piece they're responsible for and how it fits into the larger picture.
This clarity helps teams work efficiently, reducing confusion.

## Things I want to know about
