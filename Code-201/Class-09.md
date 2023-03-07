# Class-09 Reading Notes

## Baby's First Web Form And How To Structure Them.

Ahh aren't you cute not knowing what web form is. LOL who am I to talk I dont I either I'm just reading a doc and 
typing about to future me and friends that may need my present me's guidance. First let's talk about what a web 
form is in some detail. So you get to basically any modern web site and you use them pretty often and hey I can get 
access to some features when I sign up and input some info and I'll get access to stuff. Well young man or lady how 
would you interact with the web page to input that bit of information. that's where web forms come in. they are the 
bread and butter of interaction between you and a website or application. web forms let you input data which is 
usually sent to a server for processing and storage or used to update your side of the screen and update the 
interface in some way. 

You can do this by mixing it up in a HTML doc using **form control** ( if your an android user like me at the time 
you might be familiar with the word **widget**)  the web form is usually made up with a bunch of these things plus 
some additional elements to help with structure. they can be either single or multi lined text fields, drop down 
boxes, buttons,checkboxes, or radio buttons (at the time of me writing this I have no idea what a radio button is) 
they are mostly made using the input element.

>1. ***Why are forms so important in web development?***

They are what allow users to input information and allow things such as job applications to be done online line 
they make the internet interactive so that the coder isn't the only one controlling information that the webpage 
has enhancing the user experience.

>2. ***When designing a form, what are some key things to keep in mind when it comes to user experience?***

When designing a form you want to consider how a user would want to fill out the form. Some research would be 
beneficial for having optimal user experience. single column layout works best for mobile apps. You want to make 
sure the buttons look like buttons and make the most important buttons look like its the one we ant you to press 
for example on amazon the most important looking button but most importantly you want them in a place where the 
user can easily see it. 

>3. ***List 5 form elements and explain their importance.*** 

<code> <form> </code> - This element is kind of like the article or section element. they define a part of the main 
web page as a form text and holds all of the other elements in the page.

<code> <legend> </code> - This element is like the h1 for the form element its used to define what us the form for 
rather or not its a sign up or sign in etc. 

<code> <label> </code> - This element is what the user sees as what they are inputting in this section of the form 
if we didn't have this other wise they may put there birthday in the the name input section here we have to give 
the for attribute and to then apply to the input element as an id.

<code> <input> </code> -  This is the element that actually holds the text the user enters into the form. here you 
you give it three attributes.
 
 - the **type** attribute that determines what input is going to be accepted in the this section of the form that 
 can be either number,text,checkbox or ect. 
 
 - the **id** attribute that should be the same name as the for attribute from the legend element.

 - and finally the **name** element this is more for JavaScript. so we can target it in the code.

<code> <button> </code> - the button element takes all the information and does the thing to it what ever that my 
be this also take the type attribute to determine what that element does. 

## Yo We Got Events Too? JavaScript Is Kinda dope.

So we know everything is a object and thats pretty cool to think about right. So logically that would mean that 
object can experience a trigger that either changes that object or make it do a specific thing we want it to do. 
Well there a feature for that and its called events. 

>1. ***How would you describe events to a non-technical friend?*** 

So you are a person as person you go through specific experiences that shape you as a person some so when specific 
stimuli happen you respond by doing a particular thing in response or even add a new skill to your repertoire. 
first you need a state of homeostasis as a base line then you need to be able to recognize something as a stimulus 
and then you respond and adjust to get yourself to a base line. that is exactly what a event is in laymen terms.

>2. ***When using addEventListener() method, what two arguments will you need to provide?***

you want to put the **button type** that is the event trigger of the event. then you want to put the **function name** or action you want the program to do.  

>3. ***Describe the event object. Why is the target within the event object useful?***

The event object is the string in the event listener or rather the event. think of it as the thing that need to 
happen and that happens it becomes something that can be manipulated via a function that takes in the event as a 
parameter. from there you can define what happens to that event. 

>4. ***What is the difference between event bubbling and event capturing?***

Event bubbling is when you collect a bunch of event targets that can be manipulated in the event handler. The even fires from the innermost nested element targeted, and then on the next less nested element. Event Capturing is the same thing but a functions a little differently it moves in reverse goes for the outermost nested element and moves inward but they all add event targets together. 

## Things I want to know about.

1. 

2. 

3. 

4. 

5. 