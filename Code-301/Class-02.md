# Class-02 Reading Notes

## React Lifecycle

>1. ***Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?***
> Render happens before the componentDidMount
>2. ***What is the very first thing to happen in the lifecycle of React?***
> The mounting is the first thing that happens during the component life cycle. and in that the first thing that is done is the creation of the constructor.  
>3. ***Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates***
> 1 constructor
> 2 render
> 3 React Updates
> 4 componentDidMount
> 5 componentWillUnmount
>4. ***What does componentDidMount do?***
> The componentDidMount will be invoked immediately after the component is mounted. I'm a little confused as to what its purpose is but I think it will make content that is on the internet be used and make subscriptions or add api's.

## React State Vs. Props

>1. ***What types of things can you pass in the props?***
> props are kinda of like information that you want to start out with. so things like titles or headers text or um....the stating count of a number. any information or data that you want the application to start with.
>2. ***What is the big difference between props and state?***
> the biggest difference between state and props is that props comes from outside of the constructor that data is absolute and cant be changes unless it is changed by state which is to my understanding data that comes from inside of the constructor. I like to think of it like this when you read a book the information in that book would be properties and lets say that book was on how to cook a meatloaf. when you get that meatloaf recipe you decide hey I'm gonna make that meatloaf but you want to change some things in the recipe to suite you dietary restriction. So you manipulate the information in your brain and out put a new recipe that information that comes from your brain would be state.
>3. ***When do we re-render our application?***
>  when a user changes some information on the page so it is stored in state. so that that information can be re-rendered because state is the only thing that can rerender information in a constructor because that data is coming from inside of the constructor.
>4. ***What are some examples of things that we could store in state?***
> state would be anything that can be updated for example users who use a fiance tracker need to calculate how much money they need to spend each month so they would input there income and monthly expenses which would be stored in state then that information is then processed and outputs your monthly min for paying all your bills and essentials. you really want data that can be changed to my understanding in state but if the data is static you might want to use a prop.

## Things I want to know about

 1. what is UNSAFE_componentWillUpdate and UNSAFE_componentWillReceiveProps is that a phase or like a actual code?
 2. what I don't understand is the this.setState() what is the use cases for that.
