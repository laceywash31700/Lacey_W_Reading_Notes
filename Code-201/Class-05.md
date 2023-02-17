# Class-05 Reading Notes

## How to use Images in HTML and what a some common image types and what are the differences between formats?

In the Beginning when the gods of the 
Computer science made the internet the 
web was filled with only text and it 
was good boring but good. Some time 
had passed and the gods said let there 
be images to go along side these text 
so that the pions that look upon our 
creation my have knowledge and it was 
really good. I'm just kidding but the 
allegory is similar. The internet uses 
to just be just texted based and it 
was really useful for research but 
some needed images to fill in the gap 
of that knowledge. It didn't take very 
long for that to be a possibility and 
all of a sudden the internet was a 
more interesting place. With the use 
of the modest but handy dandy image 
tag <(img)> in HTML we began to be 
able to put simple images to webpages. 
you could even annotate them using the 
figure tag and use that to manipulate 
the presentation in CSS. Now in order a
for a image tag to work you really 
must use the two either of the two 
attributes scr or alt. think of the 
scr attribute as a href because it is 
connected to a URL where the image 
loads. the alt attribute is basically 
just alternative text. this is a text 
description of the image that you 
would put in the scr. this is a place 
holder for when the image cant be seen 
or the load time is dummy long because 
of a awful internet connection or the 
user is using a screen reader because 
they a visually impaired. I'll go more 
into detail in the questions with the 
questions but a quick side note 
remember how i said you can add a 
figure tag to annotate a image do this 
at the risk of down playing 
accessibility because you cant link 
the figure caption to the screen 
reader you would have to nest the 
image into the figure element and a 
figure caption element to get that 
effect. Okay that was a lot of 

information for just the elements you 
would think that would just be it but 
you have to keep in mind there are 
different image file types that you 
could use display different things in 
a browser not all image types are 
supported in all browsers but ill 
provide some that you may be familiar 
with like jpeg, gif(or pronounced jif 
idk its debatable)png, and many more 
that you or I am only hearing about 
now. if you want more info on image 
files check out [this link](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format) 

>1. ***What is a real world use for the alt attribute being used in a website?***

As I said above the alt text is used 
to provide description to what the 
image is and can be a place holder if 
the image doesn't load and can be a 
useful tool for screen readers. 

>2. ***How can you improve accessibility of images in an HTML document?***

you can add a alt or figure caption 
attribute to describe the image and 
its relevance.

>3. ***Provide an example of when the figure element would be useful in an HTML document.***

The figure element is kinda a like a 
div but for image content you could 
put multiple image tags in and videos 
or diagrams inside to provide a place 
for that content to be in a HTML doc.

>4. ***Describe the difference between a gif and an svg image,pretend you are explaining to an elder in your community.***

Ah the GIF(.gif) or pronounced JIF...
JEFF? No, it's GIF. A GIF is used 
primarily for its simple texture its 
kinda easier for the device to process 
the picture animation its usually 
pretty low quality but can be used for 
some hilarious hijinks in text 
conversation or communication. Which 
is why you see it every where on your 
phone on websites ads ect. so SVGs(.
svg) or scalable vector graphics are 
bit more higher quality. they are more 
ideal for user interfaces like when 
you use face book or order something 
off a website like amazon. they cn 
also be used for diagrams so they can 
be good for animations in movies. or 
even business presentations. I call 
them like sneaky GIFs because they are 
everywhere but more low key.  


>5. ***What image type would you use to display a screenshot on your website and why?***

I feel like that is more for a matter 
of opinion on what I'm looking for. 
Some do other things that my 
particular web page might find 
beneficial. But if I was to make a 
basic web page I'd use the either a 
PNG or a JPEG. JPEG are more supported 
in web browsers adds quality sharpness 
to photos and it is designed for 
compressing photos rather than files. 
PNG is just as supported and is 
designed more for compression so if i 
was expecting a lot of visitors to my 
site I may use this as it would 
compress the files more tightly and 
allow people to view it more easily. 
So If i was making a site for a famous 
actor i'd use PNG. but if it was for 
my bio web site I'd use a good ol JPEG.



## F%$@ing CSS and using colors to style HTML and other text elements.

So dont get me wrong I do like my 
websites colorful but CSS is is pretty 
annoying so excuse me for being a 
little blah about it. So as a human I 
gotta admit I do like me a well 
decorated website. CSS lets us do that 
by targeting elements in HTML to get 
the look that you want. now for text 
you can do the same thing of colors by 
targeting the element attribute or 
class you want in a CSS style file. 
For styling the text you would do some 
of that in an HTML file. for example 
if you wanted to break a line you 
would use the <(br)>. the rest can be 
changed by a CSS file. there are two 
types can be changed. The font styles 
and text layout.  So fonts effect the 
text font its size and wether not its 
bold or italic. Text layout affects 
the spacing.  


>1. ***Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.***
think of foreground color as the 
actual color of the content within the 
element and background color behind 
the content.Like text style or color 
behind the text the is the background 
color.


>2. ***Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?***

It would be based on how he they would 
like me to style there blog so, if i 
had full creative freedom I would make 
the text a generic color like white or 
black and I might add the text shadow 
element to give the h1 title element 
some pop. I would use the background 
color property to add some color to 
the back of the page to give it the 
vibe that the blog is all about. I 
might even make the links like a fun 
color by using a text style property 
to the <(a)> tag.

>3. ***What should you consider when choosing fonts for an HTML document?***

I think I would consider the 
background of the website. If the 
background is a color or an image its 
a little tricky for screen readers or 
the visually impaired.


>4. ***What do font-size, font-weight, and font-style do to HTML text elements?***

 Font-size - Is a property that 
 affects the size of the the text. you 
 can specify that value by percentage 
 but also by pixels ems, and rems.

 Font-weight - this is a property that 
 affects the heaviness of the boldness 
 of the font.

 Font-style - used to change the 
 writing style of the text such as 
 making it italic and default or 
 normal.   

>5. ***Describe two ways you could add spacing around the characters displayed in an h1 element.***

I think I would use the letter spacing 
or word space. 

word-spacing would allow me to add 
spaces between the words of the of the 
h1 header and give them a specific 
look you could also change that with 
the value of percentage and pixels.

letter-spacing would be a little 
obsessive but, if you really must, you 
use this property to change the 
spacing between letters Id personally 
use a text shadow property to give it 
more pzazz but thats just me 

on the bonus side I might also use 
text alignment to center them or 
manipulate content inside of the 
element box.

## Things I want to know about.

1. CSS is not my strong suit I get the 
concepts but I would like to go more 
into depth on its use cases for the 
text and font styles and when I should 
use each property when it comes to 
actual work in the wild as a front end 
dev. 