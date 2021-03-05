# Code 201 Reading Notes
hallo there i will sumorize for you some concepts that i learned from html-css book and JS book and How to Write a Git Commit Message from additional resources.
>in the end there is a quiz for you and a map for our info. &#128175;



## How the Web Works (visualization)
When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

![visualization](https://www5.0zz0.com/2021/02/27/19/968715239.png)



## Structure : its the page how its looks these are main pionts you need to understand :
* There are three types of HTML lists: ordered,
unordered, and definition.
* Ordered lists use numbers.
* Unordered lists use bullets.
* Definition lists are used to define terminology.
* Lists can be nested inside one another.

## Chapter 5: “Images” (pp.94-125)
* The <img> element is used to add images to a
web page.
* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
* You should save images at the size you will be using
them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

this will explain the idea:

![images](https://www7.0zz0.com/2021/03/05/14/723329104.png)



for more info [w3schools](https://www.w3schools.com/).

## Chapter 11: “Color” (pp.246-263) :

* css: Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.
are using.






* Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

This example will explain the idea :

![colors](https://www3.0zz0.com/2021/03/05/14/854255284.png)

* for more info: [w3schools](https://www.w3schools.com/).




## Chapter 12: “Text” (pp.264-299):

* There are properties to control the choice of font, size,
weight, style, and spacing.
* There is a limited choice of fonts that you can assume
most people will have installed.
* If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
* You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
* You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.

![text](https://www5.0zz0.com/2021/03/05/15/519459648.png)

* for more info [w3schools](https://www.w3schools.com/)



## JPEG vs PNG vs GIF :

Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.
Compression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression. This is not the case in lossy compression i.e. data loss in lossy compression is irreversible. Lossy compression algorithms always have a superior compression ratio (the ratio of size of compressed image to original image) as compared to lossless compression. However, this compression ratio comes at a cost of reduced quality that becomes more evident after zooming in on the image. This noticeable reduction in quality or distortion of the image is called compression artefact.
* JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels (read Discrete Cosine Transform), JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good result.

* PNG is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

* GIF is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.





## Cheats sheet :

Markdown is a way to style text on the web. You control the display of the document; formaing words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.you just need to make a file with .md extension on Vs code and good to go with this cheats sheet:



 HEADERS : 

```

    # This is an <h1> tag
    ## This is an <h2> tag
    ##### This is an <h6> tag

```
list :
```
     orderd:
         1. Item 1
         2. Item 2
         3. Item 3
     unorder:    

         * Item 3a
         * Item 3b

 ```  
EMPHASIS :
```
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*
```
BLOCKQUOTES :
```
> I’ve always been more interested
> in the future than in the past.
```
> I’ve always been more interested
> in the future than in the past.

LINKS:
```
http://github.com - automatic!
[GitHub](http://github.com)
```

IMAGES :
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```



table :
```
First Header | Second Header
----------- | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column
```

emoji! :
```
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
```

for more info : [markdown cheats](https://www.markdownguide.org/cheat-sheet/)


## The seven rules of a great Git commit message:
* Keep in mind: This has all been said before.
* Separate subject from body with a blank line.
* Limit the subject line to 50 characters.
* Capitalize the subject line.
* Do not end the subject line with a period.
* Use the imperative mood in the subject line.
* Wrap the body at 72 characters.
* Use the body to explain what and why vs. how.

![4](https://www4.0zz0.com/2021/02/28/22/513821309.png)


## this map for our info :


![map](https://www11.0zz0.com/2021/02/28/00/374479467.png)

## this a quiz for you :

make a page with using  images text and colors.  



>Remember : 
 * FOUCS
 * no pain no gain
 * work hard

### find more :

concepts | link
------------ | -------------
 HTML Chapter 1: “Structure” | [Structure](https://obada-gh.github.io/reading-notes/Structure)
 HTML Chapter 8: “Extra Markup”| [ExtraMarkup](https://obada-gh.github.io/reading-notes/ExtraMarkup)
HTML Chapter 17: “HTML5 Layout” | [Layout](https://obada-gh.github.io/reading-notes/Layout)
 HTML Chapter 18: “Process & Design” | [Process & Design](https://obada-gh.github.io/reading-notes/Process&Design)
 JS Chapter 1: “The ABC of Programming” | [The ABC of Programming](https://obada-gh.github.io/reading-notes/TheABCofProgramming)
 Cheats sheet | [Cheats sheet](https://obada-gh.github.io/reading-notes/cheats)

link for the github file : [gitfile](https://github.com/Obada-gh/reading-notes)






##### *writen by OBADA ALHAWJREH.*

My name is obada jaber, I’m 27 years old, I studied Mechanical engineering and i graduated from al balqa applied university, i am now a software student. [OBADA ALHAWJREH](https://github.com/Obada-gh). 

##### *Support or Contact:*

Having trouble with Pages? Check out our : [email](obada7jaber7@gmail.com) or phone number : 0781912474 or [contact support for gethub](https://support.github.com/contact) and we’ll help you sort it out. &#x1F691; &#x1F691; &#x1F691;
