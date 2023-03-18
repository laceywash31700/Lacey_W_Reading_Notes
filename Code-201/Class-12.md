# Class-12 Reading Notes

## JavaScript Canvas

Canvas seems to me like a way to make 2D graphs in webpages it is used in HTML but it looks like we are gonna be using it via DOM manipulation. The element need to attributes width and height and can just put it in the opening tag but you how we can extra. So you gotta use the DOM. You do the usual and get the id in js and and can use dot notation to decide the width and height. the are a couple of highlights that are important but you will see in the Q&A of the notes.

>1. ***What does the canvas allow a developer to achieve?***

Canvas on the large scale lets you measure metrics in your code for example if you could track how much people where viewing a users page and formulate a graph based on the time they viewed and user. On the other hand it could just let you make a graph or even 3d graphs which is kinda cool.

> 2.***What is th importance of the closing <(/canvas)> tag?***

using the closing canvas tag lets you have the text describing what  the graph is being rending be put into place in the case that the canvas is not supported in the browser or the client is using a screen reader this is called fallback content.

> 3.***Explain what the getContext() method does.***

 getContext() method allows you to render the canvas element in the HTML document. the method just take one argument as far as I know. which I'm sure would either be 2d or 3d.
>
## Chart js Documentation

so it looks to me that Chart js is kinda like node js or jquery were its a added function to Js code. You first need to add it in your HTML document via the element and give it a id attribute and name it. then you have to add it in my assumption in the meta data and like so <(script (src="https://cdn.jsdelivr.net/npm/chart.js"))><(/script)> of course omit the parenthesis by the way. and then you have to set up the chart data. you use these properties (type, data, label, dataset, and borderWidth). if you being me gets lost on this have no fear check [this](https://www.chartjs.org/docs/latest/) out for more info. there is a lot more but I figured that site can tell you way more and in more detail than I have the time to at the moment.

>1. ***What is the Chart js and how can it be brought into your project***

I don't have a context for the new project because I haven't been able to start it yet but I know I could use this in salmon cookies because I know that I can use the table I created there to render a chart of hourly sales even with the added location which is pretty neat.

>2.***List 3 different Chart types you can create using Chart js.***

So this pretty cool because you know most people are used to only seeing a few types of charts the line bar and pie are the main ones that come to mind for me but yo there a bubble one that is sooo freaking cute. You can even combine the line and bar chart together the code looks different and is not what you would expect. you would still use bar in the type property

## Easily Create Stunning Animated Charts With Chart js

from what I can see Chart js just makes making charts easier by combining the CSS and DOM manipulation more accessible to those who just dont have the time to mess around with the dom to get your charts to render properly. so if we have something like this then there has to be a thing like this for CSS too because I hate it.

>1. ***What are some advantages to displaying data via a chart over a table?***

I think some people are far more visual then others so numbers don't seem all that big when just given in raw data but when you look at a chart you can visually see how much someone sold over the other and can make client experience just more efficient i mean  computer is meant to be a thinking machine so the I know that this is wrong in some cases but the less the client has to think about number the better.

>2.***How could Chart js aid your previously created applications visually?***

I think it would take salmon cookies to the next level and make it more interesting to look. I know my numbers are big but visually seeing them would possibly help compensate for my atrocious css skills. laughing but serious.  

## Things I want to know about

1. So it looks like the objects are inside an array that are also objects and chart seems like a function but looks like a object can you expand on why that is?
2. what is a CDN is that a website and also is chart js kinda like node js and react which I hear so much about but have not a clue what they are.
