# Class-07 Reading Notes

## What is Domain Modeling?

domain modeling is a way of modeling an object literal for conceptually organizing code for use in practical use like youtube or facebook. from my understanding they use the problem domain and random numbers to predict behavior.

>1. ***Explain why we need domain modeling.***

they are a good way of predicting behaviors for users on that can be random. and measuring possible outcomes.  I'm still trying to wrap my head around it but from what I can tell it does that or rather to simplify it it is a prototype for organizing 


## What are the HTML table Basics?

Tables are used to organized data in HTML. they are defined by the <(table)> kinda like a <(ol)> or <(un)> list declaration. they use the <(tr)> tag to begin a row and the <(td)> tag as a sort of pseudo <(li)> tag for the tr tag. but you may want to use a <(th)> to define the main data the table is organizing.


>1.  ***Why should tables not be used for page layouts?***

tables once upon a time in the dark ages of the internet people used to use tables as web page layouts. This was a bad idea because they they make it difficult for people using screen reader to interpret the information being read to them affecting accessibility.they also create tag soup which makes the layout confusing and hard to debug. Finally they are not automatically responsive tables size only take up the size of the table unlike other elements like article and section width take up 100% of their parent element.

>2. ***List and describe 3 different semantic HTML elements used in an HTML table.***
(tr)- used to to define a row 

(td)- is used to contain data 

(th)- is used to make the head of a table so that the data is easier to read.

## What Are Constructors?  

Constructors are kinda like functions but for objects. They kinda are a way to make a bunch of objects at once. which are kinda useful if you have to make multiple different objects with the same properties and methods. there are different methods(being ways to do something) to create constructors. You can use the class call and then name the class in parenthesis like so 

class People(name,age){
    constructor(name,age){
        this.name = name;
        this.age = age;
    }
}

    talk(){
        console.log(`hello, my name is ${this.name} I'm saying hi from the class`);
    }
}

**you'd call it like so.** 

let person1 = new PersonClass("Tony",10);

person1.talk();
  

**this should create a object named person1 that holds the name tony and the age 10. and the talk dot notation should print the statement in the console log.**

>1. ***What is a constructor and what are some advantages to using it?***

Constructors are basically functions for creating objects. they are good for making a bunch of objects. without having to type out all that code. making it more dryer.  

>2. ***How does the term this differ when in an object literal versus when used in a constructor?***

(this) in a that constructor refers to the object parameters that will eventually be inputted for the future function. if you look at my above example you would see how it works  

## How Can I Use Constructors for Object Prototypes?

there is also a prototype method as well. it dose the same thing as a class but supposed to be and but is much older. it looks something like this. 

function PersonPrototype(name,age){
    this.name = name;
    this.age = age;
}

you can add to this function basically adding to another function using the prototype dot key word. 

PersonPrototype.prototype.talk = function(){
    console.log(`hello, my name is ${this.name}. I'm saying hi from the prototype property`);
}


here's how you would invoke the  prototype method 

let person2 = new PersonPrototype('john',20);

person.talk();

>1. ***Explain prototypes and inheritance via an analogy from you previous work experience?***

Prototypes are objects that are associated with functions, constructs, and objects kinda like a attribute that cant be seen but is still relevant for its function. I like to think of it as the glue to functions and objects. I like to think of it like this, In my current job as a food microbiologist we have clients that send in samples that we test them for listeria and other pathogens then we report to the company the results of our test from that sample and that samples lot number is sent up the supply chain till it eventually gets to the consumer. prototype inheritance is something like that. 

## Things I want to know about.

1. what is exactly the reason for using random number generators on constructor and initializing properties i dont quite understand how the process works?

2. Is modeling a algorithm that calculates or predicts something for a user?

3. how do prototype correlate to objects that have already been created are they imaginary objects for an object literal?