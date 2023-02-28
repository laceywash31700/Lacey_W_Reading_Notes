# Class-08 Reading Notes

## What is Flex box and How Do We Use Them?

the flex box is a layout mechanism that is used for laying out groups of items in on dimension. so what can you do with this flex layout. well you can.

- display content in a row or a column.
- respect the writing mode of a document.
- the flex lay out is single mode by default but can wrap onto multiple lines.
- items can be reordered visually that goes against the natural order of the DOM.
- space can be distributed inside the item so they become bigger and smaller according to the space available in their parent element.
- items can be aligned in on the cross axis. 
- space can even be distributed around the item and flex lines in a wrapped layout, using the box alignment properties.

>1. ***Flex box is designed for one-dimensional content. Explain what this means.***

One-dimensional is in meaning of some measurable extent of either length or height. We usually see things in 3 dimensions in width length and depth. so on a webpage content would naturally be in two dimensions because it has a height and width. but lets say we want out content to be in one uniform dimension. lets say length wise. flex box is designed to do just that. With two elements that have multiple lines of content that we want side by side to each other. you can manipulate it even father with the main and cross axis. the can box can be in either a row or a column not both.

>2. ***Explain the difference between the main axis and cross axis.***

So what do I mean by the main and cross axis well I would answer that by asking you to stand up and stretch out your arms. keep your back straight and arms about shoulder length apart. The dimension your arms are set up would be your the  main axis going horizontally and the cross axis would be your body standing firm to the ground going vertically. so think of geometry class with the x and y axis on a graph. You can sit down now but we can use these two axis to manipulate the flex layout. on the main axis flex items move as a group. on the cross axis on the other hand we can two major things you can move items individually or as a group so they align against each other and the flex container. 

>3. ***How can using certain properties of flex box negatively impact accessibility?***

The flex box is a fickle mechanism we can use the flex box to display items in four directions.

- row: which makes the items lay out as a row how the the flex box naturally flows 
- row-reverse: this makes the lay out as a row from the end of the flex container 
- column: this makes items layout as a column.
- column-reverse: this makes items layout as a column from the end of the flex container.

In some cases this may be a God sent but we have to remember when designing a web page we want to make sure every one can use our site without any confusion. we need to pay particular attention to how we use column-reverse and row-reverse. the reason being that when we use use these properties that sure it changes the display the way we want but this doesn't change the logic of the HTML layout. so for example if some one was using the key bored or a screen reader they will get the reversed item first. this can be pretty problematic so when doing this you may want to use thorough testing to see if this will make your site or app hard to use for some people. another thing to take into account is the writing mode to which your user would experience the content. flex displays items in the direction that our writing or script mode uses so since I'm using standard english writing mode my rows in flex would run left to right. but lets say I was designing a site for a japanese client. your row would align vertically like a column because in japanese the language is read vertically. 

>4. ***What are some advantages of using flex box over float?***

The flex box and float kind of work similarly the float property allows you to place an element on the left or right side of its container allowing text and inline elements to warp around it. it is removed from the normal flow of the page but still apart of the flow. this is useful but limiting. with the flex box it creates its own box that holds the content. and organizes it one-dimensionally making its content stay inline or even overflow you can use the reverse row to get the effect of float but more control. 

>5. ***How does this topic connect with your long term goals?***

I suppose I would need to learn about flex box with my long term goal of writing code to assist my current job in being more efficient and monitoring samples and making the content more presentable. I could use it to make buttons at the top of the software for making favorite functions of the soft ware. 

## Things I want to know about.