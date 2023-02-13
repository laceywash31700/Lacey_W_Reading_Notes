# Class-03 Reading Notes

## **So You Want to Talk About Ordered & Unordered List Huh?**

So ordered and unordered list a are basically the same. there are some minor details that I'll mention in a moment but just know you use them when you want to make a list in HTML. depending on what you want to make determines what tag element you would use for example if you wanted to make a shopping list you might want to use an unordered list. you would use the <(ul)> to start the tag minus the parenthesis of course. now if you wanted to make recipe instruction from th food you bought from said grocery store you would want a ordered list. you would use the <(ol)> tag to do so. for both you want to nest list item tag to hold what you want to put in the list keep that in mind. Now I was exactly today years old when writing this when I realized you can do more to them. there was you can change the number for ordered list. with unordered list you would use CSS. I'll go more into detail in the questions 


> ***When should you use an Unordered list in your HTML document?***

you would use unordered list when you want to make a list of of something where the order doesn't really matter. 


>***How do you change the bullet style of unordered list items?***

when you want to change the bullet style for an unordered list in CSS using the list-style-type property.


>***When should you use an ordered list vs an unordered list in your HTML document?***

You really want to use the ordered list when the list you make has to be in a specific order. For example instructions to complete a task.

>***Describe two ways you can change the number on list items provided by an ordered list?***

there are at least three ways you could do that. one would be by using the type attribute. you could change it to roman numerals. the other way is using the start attribute. with that you can really start the number where ever you want.

## **What The Hell Is The Box Model? And What It Got To Do With CSS Tho?**

So, this kind of confuses me but I'm going to do my best to explain this to you as best I can. the box model is basically the way content display is organized. this is the order going outward to inward.
1. margin
2. border
3. padding 
4. content 
these four thing can be manipulated in multiple different ways to make content display the way you like

>***Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: "The Box Model"?***
Margina the margin and Paddington the padding both love there mother Contina the content very much. they all lived inside of a cozy border that was there home. Margina and Paddington instinctively tried to stay close to Contina with no regard to her personal space. but one day Contina finally said "I need some space. so can you back off a bit. maybe five pixels" Paddington and Margina considered this and decided to move farther away from Contina. Paddinngton being more attached to his mother decided to be five pixels away inside of the border. creating an invisible boarder around them. While Margina was more adventurous and decided to be five pixels out side of the border. This gave more than enough space for Contina and they lived like this happily ever after.   


>***List and Describe the four parts of an HTML elements box as referred to by the box model.***

1. Content - The words inside of the HTML Element. that is wrapped around the padding, border and margin.

2. Padding - The invisible space between the border and the content. 

3. Border - The line or space separating the padding and the margin from each other. 

4. Margin - is the space separating the border from other margins and other content.


## **Oh ***Arrays***, How Your *Operators And Expressions* Vex  The *Conditionals* Briar That *Loops*  My Heart....But Mostly My Code.**  

did you like my haiku it mostly means nothing but it sounds good but lets talk about the key words inside starting with arrays. So, Arrays are a little tricky because I'm still learning how to manipulate them but they can be useful in my code but essentially array make a way for you to make a list of objects, strings, or integers and assign it to one variable using the [] to put those values in separated by commas. You could even have arrays inside of arrays that are also inside of arrays.confusing right think of it as a list of steps and when you get to certain part of the list there is another list that has steps and inside of that sub list is another sub list. there is more to them that I'll answer in the questions. now expression and operators I already talked about in the one of my other note so I'll build on them. as we know expressions are just units of code that resolves a value for example x = 7 expressions are composed of a variable an operator and a value for said variable. there are two types of expressions ones that have side effects for example on that holds an input from a prompt or one that purely just evaluates. now keep in mind that operators are kinda the glue that holds expressions together. and these guys can do a lot they add to a variable subtract from a variable and more.I'll share some soon that will make it more clear. now conditionals the bane of my existence in coding but mad useful. We all know about if...else and if else statements where you can make a decision tree that get pretty complicated really fast but there are other kinds of conditionals such as switch statements that are like if else but more linear and they sorta go done a list of possible outcomes and when it reaches the one you are looking for it breaks. I think a switch would be perfect to search engines. finally theres loops, I like loops their kinda cool in that if you want something to keep happening until a certain condition is met you can totally do that. I like to think of as if you want a video game character to go x amount of steps until they stop or a stamina bar in a game. there are at least three types of loop. for, while, and do while loops.  

>***What data types can you store inside of an array?***

numbers/integers,objects,arrays,strings you could even mix data types in a single array. 


>***Is the people array a valid javaScript array? If so, How can I access the values stored? if not, Why?***

 **const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];**

So this is kinda confusing but this is a valid array. It looks like the array is holding the persons name, age, occupation and hobbies. From what I can understand from the pattern null is a place holder for that value. because this value is a constant it may seem that you can't change any of the values but you and add, move, splice it and make it one long string if you wanted to using properties or think there functions im not sure quite yet. but say you wanted to add to the null in the first value. you would put people[0][0].push(hobbies) if you didn't know all arrays start a 0 in the index and because there is an array inside of the 0 index you would have to call it at a the part of that arrays index. here some tools to help manipulate arrays
1. .push() - adds to a array at the end of a array
2. .pop() - removes items from a array 
3. .indexOf() - allows you to check the index of a array. 
4. .unshift() - adds to the front of an array 
5. .shift() - removes the first item from a array 
7. .splice() - if you have knowledge of the index you can remove it from the array 

>***List five shorthand operators for assignment in javaScript and describe what they do.***

1. (/=) - divide assignment for dividing the variable by the right value for a = 4 then you would right console.log(a /= 2) which would return 2 because 4/2 is 2 

2. (**=) - the exponentiation assignment which raises the value to the right operand. for example a = 5
then you console.log(a **= 10) which would return the value of 5<sup>10</sup> which is 9,765,625 

3. (-=) - is the subtraction operator that does what you would expect subtract from the variable for the operand to the right.  

4. (+=) - does the opposite of the subtraction operator and adds to the variable 

5. (%=) - does something interesting this does the division operators math but instead of returning the whole number it return the remainder for example a = 15 then you would console.log(a %= 2) the value returned would be 1 

>***Read the code below and evaluate the last expression and explain what the result would be and why.***

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

the results should be a string and return '10 dog' because c equals false it does not have a value so it moves on to be and a just prints the string 10 dog. at least I'm assuming. 


>***Describe a real world example of when a conditional statement should be used in a JavaScript program.***

if you wanted to determine if it is some ones birthday based on the birthday the user inputs into the a website and then each day the website would compare and see if the date matches the birthday the user inputs. if on that special day you can have the website return happy birthday to that user. 


>***Give an example of when a Loop is useful in JavaScript.***

a for loop is useful if you was to make a game where every time the user press the arrow key in a certain direction they move 1 step until they stop pressing it. the while loop is useful if you dont know how long you want the loop to go on for example if you wanted a user to keep getting a question until they get a the answer right or until that ran out of attempt to answer a question 


## Things I want to know about.

1. I would need more clarification with evaluations in truthy and falsy I dont understand all the way. 