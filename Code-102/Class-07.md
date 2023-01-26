# Class-07 Reading Notes
 
## what the heck is Control Flow

the control flow is how the computer reads or rather executes your statements.
it starts from first line down unless otherwise specifed in your code a good exsample this would be a loop or if else statements.

## what are functions?

A Java function is a block of code desigined to preform a particular task 
a javascript function is executed when something invokes it (calls it).

// Function to compute the product of p1 and p2

function myFunction(p1,p2) {
return p1 * p2;
}

- they defined by the function keyword, followed by a name, folloed by parentheses ().
- there names can contain lettes, digits, underscores, and dollar signs (same rules as variables).
- the parentheses may include parameter names seperated by comma:
(parameter1, parameter2,...)
- the code that is beig run is in the curly brackets: {}

## function invocation 
- yo this function invocation stuff is pretty tight and quite interesting actually 
so code inside a function will execute when "something" invokes (calls) the functiion:

- when a event occurs(when a user clicks a button)
- when it is invoked (called) from javaScript code 
- automatically (self invoked) {which is wild cuz that didnt know they could call themselves mind blown}

## function return  

when javascript gets to a return statment the functiuon will stop executing. if 
the function was invoked from a statement, js will "return" to execute the code after the
invoking statement. functions often compute **return value.** the return valuse is "returned" 
back to the "caller"

### EX
let x= myfunction(4,3);
function myfunction(a,b){
 return a*b;
}
the result should be (12)


## so how do i use this practically?
functions are used so you do not need to rewrite code so you are not repeating yourself in 
programming it lets you add logic to js. meaning in the above ex you could put in diffrent perameters
and the function should mutiply the result of any two integers 
think of functions as its own seprate code that 

## Things I want to know about.
I'd like dive more in depth into operators to better code loops and functions but I think more that will come with time.