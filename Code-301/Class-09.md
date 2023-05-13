# Class-09 Reading Notes

## Functional Programming Concepts

> 1. ***What is functional programming?***
> functional programming is a pattern of programming where the use of pure functions, immutable data, and declarative programming style is heavily emphasized. it uses small functions that are made for reuse rather than modifying the state.
>
> 2. ***What is a pure function and how do we know if something is a pure function?***
> a pure function is a function that produces the same result every time without changing anything globally or otherwise no side effects for example
    const add = (a,b) => a+b
> this example only takes in the argument of a and b but and adds them together and the return is alway a+b.
> 3. ***What are the benefits of a pure function?***
> They are much easier to test.
>
> 4. ***What is immutability?***
> Immutably  if we are talking functional programming is an object or data structure that it cannot be modified after it has been created. In other words, immutable objects cannot be changed, and any operation that appears to modify an immutable object actually creates a new object with the updated value.
>
> 5. ***What is Referential transparency?***
>
Referential transparency is a property of functions in which a function call can be replaced by its return value without affecting the correctness of the program. In other words, if a function f is referentially transparent, then calling f(x) always returns the same result y for the same input x, and you can replace f(x) with y anywhere in the program without changing the behavior of the program.
>

## Node JS tutorial for Beginners

> 1. ***What is a module?***
> its another javascript file that does a type of functionality we do this sorta in react but instead of using import we use require.
>
> 2. ***What does the word ‘require’ do?***
> require is like import from react it just connects two modules together in node.
>
> 3. ***How do we bring another module into the file the we are working in?***
> we have to use module.export in order to do that is kinda like export in react but u have to make it equal to the data or code you have in the exported module. 
>
> 4. ***What do we have to do to make a module available?***
>once we require it through a file path we have to initialize it to the page by giving it a value. then you can use that code so in a way its more like express.js
>

## Things I want to know about
