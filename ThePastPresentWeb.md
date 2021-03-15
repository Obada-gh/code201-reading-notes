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

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS:

ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

What we really want is

* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server

### A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5:

In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.

userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.

### USING HTML5 STORAGE:
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

### TRACKING CHANGES TO THE HTML5 STORAGE AREA:
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.

The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)

if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};

### BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS:

While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.

One vision is an acronym that you probably know already: SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite. This early prototype later influenced the creation of the Web SQL Database specification. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to do things like this from JavaScript:
### Example:
```
↶ actual working code in 4 browsers

openDatabase('documents', '1.0', 'Local document storage', 5*1024*1024, function (db) {
  db.changeVersion('', '1.0', function (t) {
    t.executeSql('CREATE TABLE docids (id, name)');
  }, error);
});
```






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

link for the github file : [gitfile](https://github.com/Obada-gh/reading-notes/blob/main/class-02.md)






##### *writen by OBADA ALHAWJREH.*

My name is obada jaber, I’m 27 years old, I studied Mechanical engineering and i graduated from al balqa applied university, i am now a software student. [OBADA ALHAWJREH](https://github.com/Obada-gh). 

##### *Support or Contact:*

Having trouble with Pages? Check out our : [email](obada7jaber7@gmail.com) or phone number : 0781912474 or [contact support for gethub](https://support.github.com/contact) and we’ll help you sort it out. &#x1F691; &#x1F691; &#x1F691;
