# Class-10 Reading Notes

## Understanding The JavaScript Call Stack

> 1. ***What is a ‘call’?***
>  A function invocation any one function invocation is a a call.
>
> 2. ***How many ‘calls’ can happen at once?***
> It all runs one at a time. from top to bottom. usually in synchronicity.
>
> 3. ***What does LIFO mean?***
>  Last In First Out. I like to think of it like this when you write your code it you righting from top to bottom so the last thing you write would naturally be at the bottom so the last thing you wrote would be the first to be called and the stack will work its way back up.
>
> 4. ***Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.***
>  
Call Stack:

1. main()
2. functionA()
3. functionB()

 function main() {
  console.log("Inside main()");
  functionA();
  console.log("Back to main()");
}

function functionA() {
  console.log("Inside functionA()");
  functionB();
  console.log("Back to functionA()");
}

function functionB() {
  console.log("Inside functionB()");
  console.log("Returning from functionB()");
}

// Initial call to main()
console.log("Starting program");
main();
console.log("Program execution complete");
>
> 5. ***What causes a Stack Overflow?***
> A stack overflow happens when a function is called recursively without a end point kind of like a infinite loop but with function calls.
>

## JavaScript error Messages

> 1. ***What is a ‘reference error’?***
> Its an error when you use a variable or object that hasn't been defined yet in the stack.
>
> 2. ***What is a ‘syntax error’?***
> a grammer error in you code like a bad semicolon here or a missing one there but you linter usually catches that.
>
> 3. ***What is a ‘range error’?***
> its when you try to give something a invalided range so like an string that has a length of 14 but you assign it -15 you get a range error because the length of the string cant be any less then 14.
>
> 4. ***What is a ‘type error’?***
> so this one was confusing at first but once you get it you get it it just means that when you are passing a variable to a function the variable type may not be what you think it is for example you may think you are passing a integer but really you are passing down a string.
>
> 5. ***What is a breakpoint?***
> its a debugger tool that your browser and vs code has where you can literally say hey code stop here and then you can decide where to go next to either keep going go to the next function or go to the previous function.
>
> 6. ***What does the word ‘debugger’ do in your code?***
> it will define a breakpoint for debugging.
>

## Things I want to know about
