# Class-37 Reading Notes

## Multiple Reducers Example

> 1. ***Why create multiple reducers?***
>  As your application grows, the state management logic can become complex. Having multiple reducers allows you to split the logic into smaller, manageable pieces. Each reducer can be responsible for managing a specific slice of the global state, making it easier to understand, debug, and maintain your code.
>
> 2. ***How would you combine multiple reducers?***
> Combining multiple reducers in Redux involves using the combineReducers function provided by the Redux library. 
>
> 3. ***How will you manage state as an immutable object? why?***
> Managing state as an immutable object in Redux (or in any state management system) involves ensuring that the state cannot be changed directly. Instead, whenever you want to modify the state, you create a new copy of the state with the desired changes. you do this for a couple of diffrent reason a few being that it limits bugs and give predictablility for your code. and most cool time travel debugging because OF how we process actions we can go back in time and go to a previous state. 
>

## Redux Docs: Using Combined Reducers

> 1. ***combineReducers is a utility function to simplify the most common use case when writing _**Redux reducers** .***
>
>
> 2. ***Explain how combineReducers assembles the new state tree.***
>  It assembles a new state tree by calling each reducer with the slice of the state that it manages and combining the results into a single object.
>
> 3. ***How would you define initial state in an app using combineReducers?***
> When using combineReducers in a Redux application, each individual reducer can have its own initial state. You can define the initial state for each reducer right in the reducer f
>


## Redux Docs: Combined Reducer Syntax

> 1. ***Why will you want to split your reducing functions as your app becomes more complex?***
> like managing mutable Splitting reducing functions becomes essential as your app becomes more complex for several reasons:
>
> 2. ***The **compose** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to **reduce**.***
>
>
> 3. ***What is a popular convention when naming reducers?***
> slice
>


## Things I want to know about
