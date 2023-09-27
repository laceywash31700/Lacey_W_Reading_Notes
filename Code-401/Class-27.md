# Class-27 Reading Notes

## Thinking in React

> 1. ***Summarize the five steps of thinking in react.***
>  - step 1: is to make sure you make your UI is broken up into a component hierachy this is a lot like modululization in the back in. react funtions in a simiular way where you split up the funtionality or interatabilty of you front end ideally each component would do one thing.
> - step 2: is to start by building a static version of the UI no interactivity this is like a blue print for when you start adding interactive code functionlity.
> - step 3: next is to start thinking about what you state is this is data that you want your UI to remember and you dont want to repeat yourself here and keep it to the data you absolutly need.
> - step 4: next is to find out which component will your state live in you would do this by identfying the compentent that render based on state and find the closest common parent.
> - step 5: then you want to make sure that you data will flow inversly to update state for the parent component. in other words how would you hoilst state from a child node to a parent?


## State: A Component’s Memory

> 1. ***What is one reason a local variable isn’t sufficient for managing a React component?***
>  Because when react is rendering it renders the component from scratch so it starts over from the beginning as if the data never changed even though the logic says to update when the data changes locally the component doesnt recognize the change and doesnt render.  
>
> 2. ***What is the argument to the useState hook, and what are the two parts of its return array?***
> the argument would be the value of the state you want to set so if you want to start a 0 in an array you want to put 0 in usestate. but you first want to set state pairs which is a array for the variable you pass in use state which in this case would be index and the set index function that increments the index. which should be defined as its own function in a handlesubmit function you pass in a own click function
>
> 3. ***How can Component A access state from Component B?***
> The right way to do it in React is to remove state from child components and add it to their closest shared parent. 
>

## Things I want to know about
