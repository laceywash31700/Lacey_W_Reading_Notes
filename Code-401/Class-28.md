# Class-28 Reading Notes

## useEffect hook

> 1. ***What is the main intended use case for the useEffect hook***
> It reminds me of socket server connections so iF I had a server that operated as a chat room you would use that 
to assign the route and the room connector 
The useEffect hook is for building user interfaces. Its 
main intended use case is to handle side effects in functional components. Side effects in React typically 
include data fetching, subscriptions, or manually changing the DOM.
>
> 2. ***How does the effect’s logic interact with the component?***
> seEffect is commonly used for fetching data from APIs or databases. You can initiate a network request inside 
> the useEffect function and update the component's state with the fetched data when the data is available.
>
> 3. ***What is the importance of the return value from the effect’s logic function?***
> the return value from the effect's is used for cleanup operations. This 
> return value can be a function, often called the cleanup function.The cleanup function serves several 
> important purposes, making it a crucial aspect of using useEffect correctly
>

## Things I want to know about
