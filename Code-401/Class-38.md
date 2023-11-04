# Class-38 Reading Notes

## async actions

> 1. ***Why use Redux middleware?***
>Redux middleware is a powerful and flexible mechanism that allows you to intercept, modify, or extend the behavior of Redux's dispatch function. Middleware functions sit between the action creators and the reducers in the Redux application flow, providing a way to add extra functionality to the dispatch process
>
> 2. ***Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.***
>The process starts when a React component dispatches an action. This action is a plain JavaScript object describing the type of action to be performed, and optionally, some payload data.nstead of reaching the reducer directly, the action first goes through middleware. Middleware intercepts the action before it reaches the reducer, allowing you to perform asynchronous operations or other side effects.
>
> 3. ***How are we accommodating async in our Redux app?***
>handling asynchronous operations typically involves using middleware like Redux Thunk, Redux Saga, or Redux Observable. These middleware libraries allow you to write action creators that return functions instead of plain action objects. These functions can then dispatch actions asynchronously, enabling you to handle async operations like data fetching, API calls, or timers. 
>

## thunk middleware

> 1. ***Why would you need redux-thunk middleware?***
>Redux Thunk middleware is used in Redux applications to handle asynchronous operations, such as data fetching, API calls, and other side effects. Redux Thunk middleware allows you to dispatch asynchronous actions in Redux. Regular Redux actions are plain JavaScript objects, but with Thunk, action creators can return functions. 
>
> 2. ***Redux Thunk middleware allows you to write action creators that return a __**functions**__ instead of an action.***
>
>
> 3. ***Describe how any return value from the inner thunk function will be made available.***
>In Redux Thunk, the inner thunk function can return a value, but that value is not used by the Redux store or middleware. The primary purpose of the inner thunk function is to perform asynchronous operations and dispatch actions based on the results.
>


## Things I want to know about
