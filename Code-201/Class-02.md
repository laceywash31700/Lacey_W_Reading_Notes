# Class-02 Reading Notes

## Why Is HTML Text And Formating so imprtant?

HTML formating is how HTML gives structure to a webpage they way that it is intended to be seen by the 
developer. The structure of the content makes the reading exprience easier for the client acessing this 
information. We use semantics to specify the content in each element.The use of the elements is really up 
to the developer of the site as long as it follows the hiearchy of the element tag. the structure of 
content also make it possible to use CSS and JavaScript to target the content. 

> ***Why is it important to use semantic elements in your HTML?***

Semantics make it possible to give meaning to the content in which we are coding. For example, we would not 
put the contents of an entire chapter in an book in an <h1> element because, the reader would read the 
content in a large bold text making it difficult for screen readers or even search engines to navigate the 
website. It would also make it harder to target this element in JS and CSS.From my understanding, you would 
use <p> tags or even a <article> tag to do this as it's much easier to absorb the content and its also just 
organized.

>***How many levelss of headings are there in HTML?***

> there are 6 heading elements in HTML <h1>,<h2>,<h3>,<h4>,<h5> and <h6>

>***What are some uses for the <sup> and <sub> elements?***

(<sub>) is a element that stands for **subscript** and (<sup>) stands for **superscript**. They are 
generally used to make the th in 25th day of the month a superscript or the chemical composition of caffine 
C8H10N4O2 a subscript.  

***When using the <abbr> element, what attribute must be added to provide the full expansion of the term?***

You use the tile attribute in a <abbr> tag so that screen readers will know what the full text mean. for 
example if I wrote ISP in a p tag and the screen reader read it it would sound out isp. but if I but in the 
abbreviation tag Internet Service Provider that would make it screen reader say the whole expansion of the 
abbreviation.this is a means of adding accessiblity to a webpage.

## What Is CSS And Why Does It Matter in Relation to HTML?

If you just made a website using HTML, our websites would be boring and to honest kinda ugly. CSS changes 
that and lets us add a little or lot of pazzaz to the presentation of your Website. You usally put this in 
a another file that is linked to the HTML file.this is where structure is mad important for the HTML fine. 
How it works is that you target an element in your HTML file. you can go even deeper and target attribues 
too like IDs and Classes. you put them in {} and inside of them you put what you want to change weather 
that be the style padding,color,size ect. it can deeper than that but thats what I understand as the basics.

>***What are ways we can apply CSS to our HTML?*** 

You can make a style attribute and just change the size or color you want. or you can use a style tag and 
put in the CSS code you want or you can and this is the most common method you could make a seperate CSS 
file and put in the code that targets the elements or attributes you want to style.

>***Why should we avoid using inline style?*** 

From my understanding if you use too much inline code you would make your  HTML file really long and clunky 
and hard to read. Also, its just not efficent and coding is all about efficency. 

>***Review the block of code below and answer the follwing question***

>***1) What is representing the selector?*** 

The selector would be the h2 which in you HTML would be your <h2> tag this is what we are targeting 

>***2) Which components are the CSS declarations?***

the declarations would be color: black; and padding: 5px;
the declaration is composed of the property we want to change which is this case is color and padding and 
the value we want to make that property which is the black and 5px

>***3) Which components are considered properties?***

color and padding are properties.

>   h2 {
>     color: black;
>    padding: 5px;
>   }

## What Are The Basics of Javascript and how does it Apply To A Websites? 

Now it is important to understand JavaScript is a beast. It can get pretty wild in there but I'll expalin 
it to the best of my Knowledge.This programming language in a nut shell adds dynamic to your webpage or 
app. this is what actually lets you do the thing you want to do on your web page for example if you wanted 
music to play when they click and certain part of the page. it do soooooooo much more but that one its 
basic applications.To K.I.S.S it, think of it basic logic for the webpage to follow. It also also you use A.
P.Is to add code you basically didn't write but yo its makes your life sooo much easier and these A.P.Is 
are bascally functions that do just that adds a function to your webpage. you also create functions too to 
do basically almost anything you want to do.its important to know two things everything and I mean 
**EVERYTHING, IS A OBJECT AND CAN BE STORED IN A VARIABLE** in JavaScript. Also JavaScript **RUNS CODE THE ORDER IT IS CODED AND WORKS ITS WAY DOWN**

>***What data type is a sequence of text enclosed in single quote marks?***

That my friend is a string.To clarify stings can be in either single or double quotation marks. 

>***List 4 types of JavaScript operators.***

So, strap in kids we going back to school. just for basic arthmitic operators(and just in case you didnt 
know an operator produces a result based on the two values or variables.)  you'd use (+) for addition,(-) 
for subtraction,(*) for multiplication,(/) for division. Now this part is a little confusing but bare with 
me. the (=) assigns a variable, (===) this is strict equality meaning it would tell the computer hey look 
at two variables and see if they are equal and return true/false. and finally, (!) which is just not which 
can be used all types of trippy things that are kinda cool but confusing at my current level of knowledge. 

>***Describe a real world problem you could solve with a function***

So I consider functions the bread and butter of JavaScript. It can simple and short and sweet or dummy 
thick and long. And because of that you can use them solve literally anything you can think of. like what 
velocity do i need to be in also taking account for mass to break the sound barrier. or finding a 
geolocation from where the client is from the server. the possiblities are endless 

## What are conditional Statements?

So, I'm actually struggling with this stuff but, I get the concept. So imagine your brain and how it works 
**the logic of it.** Im gonna use stop signs and how we operate when we drive as an example. When we see a 
stop sign you stop right. the variable stop sign and that is equal to stop your car when you get to it. or 
at least you should. Now, **if** you are the first one to get to the stop sign **While** other cars are on 
the road which are **both conditions that need to be met**, you have the right of way to go, or **else** 
you don't because you are not the first car to drive up the the stop sign. you then reevaluate those 
**conditions** and it can be either true or false and based on the result you go. that is all a conditonal 
statement is and that are really really useful in programing. it can be boolean or loops or like arrays i 
think dont quote me on that but yeah that is what a condition is. there is more to it like **else if** and 
stuff but you get the concept I hope.

>**An if statement checks a(*condition*)and if it evaluates to(*true or false based on the perameters of the if statement*),then the code block will execute.**

>***What is the use of an *else if?***

So, **else if is really complicated and simple at the same time.** So in **if** statements **you have a condition that can be either true or false based on what perameters you set the condition.** if that 
condition meets the perameters you set then you run the code block under the if **but, lets say those perameters of the if statement are not met** so you go to the **else statement but there are conditions you want to be accounted for before going on the else statement** this is when **you use the else if statement because logically we as humans can understand that two things can be true or false so we tell the computer to account for that.** now you can do this multiple times until you get to the ultimate else statement that 
end the conditions because every thing would need to be true or false again depending on how you set the 
perameters for it to go to last else statement.  

>***List 3 diffrent types of comparison operators.***

I already meantioned two up above in the JavaScript section but go for ones that I didnt see in the 
reading. 

- (!=)- not equal
- (==)- equal to as in arithmitic not be confused with (===) which would make some thing true or false.
- (>,<)- **greater than** would be **on the left** and **less than** would be **on the Right** its easy to 
remember for me because I always get them confused is look at the way the arrow is pointing. greater than 
is going to the direction you read and less than goes the opposite direction.

***pro tip***
if you add a (=) to either(>)(<) to the right of it you make it **greater than or equal to** and **less than or equal to**

>***What is the diffrence between the logical operators (&&) and ? ***

**(&&)** is just saying **and**
**(||)** is saying **or** this is the shift plus the backslash key on the keyborad
from my knowledge they are used in loops 

## Things I want to know about.

1. How would I use a blockquote element properly and what would be its applications?

2. what does &lt; and &gt; do?

3. I would need some clarification on the cite attribute why would I use this? 