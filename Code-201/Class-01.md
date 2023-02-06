# Class-01 Reading Notes

## Clients and Servers 
- think of **clinets** as a your phone 
or computer and the web browsers that 
search the internet for websites.
- think of of **servers** as a big 
storage unit or computer to be 
specific, that holds webpages, sites 
and apps so when a client(your device) 
wants to access this those webpages 
you download it so it can be veiwed on 
your device.

there is so much more to it but for 
now lets decribe what happens when you 
want to access a website.
### what happens when I want to access a website?
so imagine the client as a house and 
the server as a shop. 

1. The browser goes to the DNS server, 
and finds the real address of the 
server that the website lives on (you 
find the address of the shop).

2. The browser sends an HTTP request 
message to the server, asking it to 
send a copy of the website to the 
client (you go to the shop and order 
your goods). This message, and all 
other data sent between the client and 
the server, is sent across your 
internet connection using TCP/IP.

3. If the server approves the client's 
request, the server sends the client a 
"200 OK" message, which means "Of 
course you can look at that website! 
Here it is", and then starts sending 
the website's files to the browser as 
a series of small chunks called data 
packets (the shop gives you your 
goods, and you bring them back to your 
house).

4. The browser assembles the small 
chunks into a complete web page and 
displays it to you (the goods arrive 
at your door — new shiny stuff, 
awesome!).

## Re-Introduction to HTML

HTML or Hyper Text Markup Language is 
the foundation or skeleton of a 
website. its composed of **element** 
that are used to organize information. 
think of them as boxes that hold 
specific parts of your webpage. 

### Anatomy of an HTML element 

- An element goes in <> with the name 
of the element name inside this would 
be the **opening tag.** 
- </> would be the **closing tag** 
with name of the same element that was 
in an opening tag 
- You can even have a element inside 
of a element this is called **nesting**
- You can assign attributes to a tag 
essentially which is a kin to labeling 
the box there are two types of 
attributes 
    1. **Class**- a attribute that 
    labels some of your elements.
    2. **ID**- labels a specific 
    element.
- Not all elements follow the pattern of an opening tag, 
content, and a closing tag. Some elements consist of a 
single tag, which is typically used to insert/embed 
something in the document. Such elements are called **void element**

### What is Metadata?

 Metadata is data that descrides data. Some examples of metadata would be the <head> element or the <title> element. this is data that is not seen by the client. 
## Things I want to know about.

1. Why is metadata so important?

2. Can I have more information about void elements and its uses?

2. What is a TCP and how does it relate to a DNS?

4. Would my Wifi effect my DNS?

the more I learn the questions I have but I'm sure I'll learn it in due time. 