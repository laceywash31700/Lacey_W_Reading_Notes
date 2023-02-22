# Class-06 Reading Notes

## Oh Objects how I have waited for thee.

My teacher's been talking about objects for a while now and since then ive been curious. Objects look to be like a variable that holds multiple values with related data types. it can hold arrays, integers, strings, and functions. so when I think about manipulating objects I think of npcs in a video game they are littoral objects that have designated strings they can say and so on.

>1. ***How would you describe an object to a non-technical friend you grew up with?***

so lets say you have a man right this man name is Reese his last name is Thompson. Reese is 27 years old. and he like to mountain climb. so he had the ability and understands the logic of mountain climbing. When Reese introduces himself he says'Hey whats up?' almost every time you see him unless something changes him doing the routine. Reese lives in New Hampshire and has a husband name Stephen. You know a lot about Reese so if Reese is a man that would be the name of the variable man. and everything we know about Reese would go in that variable making man an object. 

>2. ***What are some advantages to creating object literals?***

In the last example for Reese Thompson 
the variable that holds Reese's self 
man would be the object literal it's 
just a fancy word for a variable that 
is a object that holds multiple 
values. so an object advantages would 
be that lets say you where in social 
media right so your profile would 
probably be person and have a lot of 
different data for just you in that 
profile. Imagine sending 60 different 
request for when you want to see 
someone on facebook that would be 
ridiculous sending the request for a 
single object literal is way more 
efficient. They are also easier to 
work with than arrays because they are 
easier to identify individual items by 
name.   

>3. ***How do objects differ from arrays***

objects differ from arrays though the 
fact that they dont have a index. They 
have use thing like dot notations and 
bracket notations. For example if i wanted to get some one by there name fist and last name in a object like in my last example for Reese I would code man.name.first and man.name.last. the dots specifics what I want to call from the object. Bracket notations make it easier for programmer to access information by the name in the object for example man["age"] would be the age of Reese which would be 27 years old. 

>4. ***Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.***

In a objects property name is held in a variable then you can't use dot notation because to access the value. but thats were bracket notation comes in. so if you were making a function that would take in the value form the the object to return the value you are looking for in the function.  

>5. ***Evaluate the code below What does the term (this) refer to and what is the advantage to using (this)?***
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

from what I understand  this is referring to this object which is dog. and it allows you to refer the variables without naming it as the object literal. this also allows you to use re use code kinda like a function.

## So what the DOM? And I wont even begin to make a dirty joke there. low hanging fruit. 

The DOM(DOCUMENT OBJECT MODEL) refers to the document hierarchy in a code starting the the document and allows for manipulation of the snippets of code inside of the document called nodes. 

>1. ***What is the DOM?***

The DOM is the model to which code is organized in webpage. I like to think of it as a tree with the document being the root node and every other element being the child node or siblings this model makes it possible to manipulate the document to add or remove what you may want. 

>2. ***Briefly describe the relationship between the DOM and JavaScript.***

JavaScript and the DOM go hand in hand making it possible to add or remove things inside of the document inside of javaScript instead of in HTML or CSS. 

## Things I want to know about.

1. the DOM still confuses me but I hope that the lab will answer some of my questions I may have.

2. I would like to know more in depth when it would be appropriate to use the DOM in my daily coding and what are some benefits to using it? 