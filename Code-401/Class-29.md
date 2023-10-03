# Class-29 Reading Notes

## Extracting State Logic into a Reducer

> 1. ***What is the motivation for adding a reducer?***
> The motivation for using a reducer in React, whether with useState or useReducer, lies in managing state in a more organized, predictable, and maintainable way. 
>
> 2. ***What are actions in the context of a reducer? How are they different than setting state directly?***
>  When you use a reducer with useReducer in React, you dispatch these action objects to the reducer function. The reducer function then takes the current state and the action, processes the action, and returns a new state based on the action's type and payload. This structured approach helps manage state transitions in a predictable way, making your application more maintainable and easier to debug.
>
> 3. ***What common list operation is useReduce named for, and why?***
> useReducer hook, the concept of reducing an array of values to a single value is metaphorically applied to state management. Instead of operating on an array, useReducer works with the state object, allowing you to dispatch actions to modify the state.
>
> 4. ***When should you switch from useState to useReducer?***
> Use useState when:
Simple State Logic: If your state logic is straightforward and involves updating a single piece of data without complex transformations, useState is usually sufficient and more concise.

Local Component State: When the state is limited to a single component and does not need to be shared across multiple components or deeply nested components, useState is a good choice.

Performance: For small-scale applications or components where performance is not a critical concern, useState is generally faster and simpler to use.

Switch to useReducer when:
Complex State Logic: If your state logic becomes complex, involving multiple sub-values or intricate state transitions, useReducer can make your code more readable and maintainable. It helps manage more complex state logic by encapsulating it within a reducer function.

Shared State: When the same state needs to be accessed or updated by multiple components, using a useReducer with a context can be a good solution. This allows you to avoid prop drilling (passing down state through many layers of components) and manage the shared state centrally.

Predictable State Transitions: If your state transitions need to be predictable and traceable (for debugging purposes), useReducer encourages a more structured approach by enforcing a pattern where state transitions are determined solely by the action dispatched to the reducer.
>
> 5. ******
>
>

## PLACEHOLDER2

> 1. ******
>
>
> 2. ******
>
>
> 3. ******
>
>
> 4. ******
>
>
> 5. ******
>
>
> 6. ******
>
>

## Things I want to know about
