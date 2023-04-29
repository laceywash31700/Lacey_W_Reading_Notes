# Class-05 Reading Notes

## Thinking in React

> 1. ***What is the single responsibility principle and how does it apply to components?***
> Its the idea that components should be doing only one thing ideally. if the component ends up growing then we should septate them into smaller sub-components.
> 2. ***What does it mean to build a ‘static’ version of your application?***
> it basically what we have been doing in the beginning with gallery of horns all we where doing was making the information render so we can see it on the page then we slowly added interactivity. its basically creating a proof of life application.
> 3. ***Once you have a static application, what do you need to add?***
> after you made a static model you might want to add some interactivity and functionality dat bih. At this point you would add state to change up your data.
> 4. ***What are the three questions you can ask to determine if something is state?***
> Does it remain unchanged over time?
> Is it passed in from a parent via props?
> Can you compute it based on existing state or props in your component?
> 5. ***How can you identify where state needs to live?***
>  well for one is it something that need to be changed in this particular component is a good start. but for the most part state is usally inside of a common parent component but if you cant decide you can just make component and have it solely hold state and pass it down to the the other components.

## Higher Order Functions

> 1. ***What is a “higher-order function”?***
> so for what I can understand it look like its like a constructor function but for functions. or rather it is a means of manipulating functions so that they can be more dynamic but im still figuring it out.
>
> 2. ***Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?***
> It is returning a function that take in whatever number and compares it to (m) which I don't know what (m) is yet but from what i can understand it is making a new function like a constructor would make a new object. maybe (m) is the new number after that is put in as a parameter after the new one is defined.
>
> 3. ***Explain how either map or reduce operates, with regards to higher-order functions.***
> so a higher order functions produces or manipulates values kinda like map and reduce that apply a call back function over every value in the index but one literally reduces the array into a singular object or integer which is reduce and the other performs a functions on each value in the array. 
>

## Things I want to know about
