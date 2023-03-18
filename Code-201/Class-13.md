# Class-13 Reading Notes

## Local Storage and How To Use It On The Web

local storage is how we store data on user devices via cookies and HTML<sub>5<sub> they can used be used to cut down load time for devices and save information for less web traffic. 

>1. ***Why would a developer use local storage for web applications?***

Because HTTP is reset every time a user closes out the web browser it's hard for users to access saved information they have previously viewed or saved on a website so to maintain that information or state web developers can use there local storage to maintain that information without using remote servers.

>2.***What information should not be stored in local storage?***

Cookies because they can be easily exploited by people trying to to spy on their browser behavior. And the crazy part is that they are used everywhere.

>3.***Local storage can store what type of data? How would you  convert it to that type before storing?***

Local storage seems to be to store whole web pages and input data locally on user storage you can even store whole interface states. but I think you are talking about the fact that the data type is stored as a string.  so you would would get around this by using the JSON.stringify() and JSON.parse() methods? I don't Know how they work fully.

## Things I want to know about

 1. What does the reading mean BY vanilla and the favorite flavor is this a way to set up the local storage in html5?

 2. Also I wasn't even aware html had a 4, 3, and 2 I always thought there was 1 are these versions and is this related to DOM in some way for some reason my brain is looking at everything in DOM references so I'm trying to reinforce that?

 3. what is ajax() and I tried to mess with jquery but I don't really understand it fully is it a library like chart js and how can you use it without having to download it on besides ubuntu?