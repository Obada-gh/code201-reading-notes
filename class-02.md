# Code 201 Reading Notes
hallo there i will sumorize for you some concepts that i learned from html-css book and JS book and How to Write a Git Commit Message from additional resources.
>in the end there is a quiz for you and a map for our info. &#128175;



## How the Web Works (visualization)
When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

![visualization](https://www5.0zz0.com/2021/02/27/19/968715239.png)

## Chapter 2: “Text” (pp.40-61) :

Structure : its the page how its looks these are main pionts you need to understand :
* HTML pages are text documents.
* HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
* Tags are often referred to as elements.
* Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
* Opening tags can carry attributes, which tell us more
about the content of that element.
* Attributes require a name and a value.
* To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

this will explain the idea:

![structure](https://www9.0zz0.com/2021/02/27/18/436061789.png)

text are immportant you can see this examples to modify your text:

![1](https://www3.0zz0.com/2021/02/28/19/211929568.png)
![2](https://www3.0zz0.com/2021/02/28/19/658338179.png)
![3](https://www7.0zz0.com/2021/02/28/19/324196322.png)
![4](https://www3.0zz0.com/2021/02/28/19/654452876.png)

for more info [w3schools](https://www.w3schools.com/).

## Chapter 10: Ch.10 “Introducing CSS” (pp.226-245) :

* css: Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.
are using.

This example will explain the idea :

![4](https://www12.0zz0.com/2021/02/28/19/408535291.png)

* also we cam make an external path for css for more info: [w3schools](https://www.w3schools.com/).




## Chapter 2: “Basic JavaScript Instructions” (pp.53-84) :

* A script is made up of a series of statements. Each
statement is like a step in a recipe.
* Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.
* Variables are used to temporarily store pieces of
information used in the script.
* Arrays are special types of variables that store more
than one piece of related information.
JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
* Expressions evaluate into a single value.
* Expressions rely on operators to calculate a value.

![java](https://www6.0zz0.com/2021/02/28/20/591067837.png)

* for more info [w3schools](https://www.w3schools.com/)

This is example you can use it to your layout :
```
<header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
<footer>
&copy; 2011 Yoko's Kitchen
</footer>
```
![nav](https://www9.0zz0.com/2021/02/27/18/436061789.png)


## Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)
* Conditional statements allow your code to make
decisions about what to do next.
* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
* Logical operators allow you to combine more than one
set of comparison operators.
* if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.
* switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
* Data types can be coerced from one type to another.
* All values evaluate to either truthy or falsy.
* There are three types of loop: for, while, and
do ... while. Each repeats a set of statements.

* Examples

![1](https://www7.0zz0.com/2021/02/28/22/709638801.png)
![2](https://www7.0zz0.com/2021/02/28/22/748810749.png)
![3](https://www7.0zz0.com/2021/02/28/22/876862974.png)





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

write a five horizontal stars with the for loop in javascript !!



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

link for the github file : [gitfile](https://github.com/Obada-gh/reading-notes/blob/main/class-01.md)






##### *writen by OBADA ALHAWJREH.*

My name is obada jaber, I’m 27 years old, I studied Mechanical engineering and i graduated from al balqa applied university, i am now a software student. [OBADA ALHAWJREH](https://github.com/Obada-gh). 

##### *Support or Contact:*

Having trouble with Pages? Check out our : [email](obada7jaber7@gmail.com) or phone number : 0781912474 or [contact support for gethub](https://support.github.com/contact) and we’ll help you sort it out. &#x1F691; &#x1F691; &#x1F691;
