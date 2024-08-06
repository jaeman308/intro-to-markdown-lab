# How to write an HTML5 Boilerplate 

![htmlimage](https://media.istockphoto.com/id/1408445036/photo/programming-web-pages-with-html-and-css-code-on-a-desktop-computer.webp?b=1&s=170667a&w=0&k=20&c=8bzVsHnZpYnd11a97dRNSgGuuzXMP3qA5zqTGB7j97c=)

The foundation of a website is always in important. One of the top template that is used in HTML is the HTML5 boilerplate.

***Eacxmple of HTML 5 boilerplate***

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>
  </body>
</html>
```


### DOCTYPE html:
The first line in your HTML code is the declaration which is called doctype. THe doctype tells the browser what version of HTML the page is written in. 

***Example:***

``` 
<!DOCTYPE html>
```

Note: 
If you forget to include this line of code in your file, then some of the HTML 5 tags may not be supported by the browser. 
Such as ``<article>`` ``<footer>`` and ``<header>``.

### HTML Root Element: 
The ``<html>`` tag is the top level element of the file. You nest the ``<head>`` and ``<body>`` tag inside of the ``<html>`` tags. 

***Example:***

```
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
Note: The lang attribute inside of the ``<html>`` tag sets the language of the page.  It is also good to include it for accessibility reasons, because screen readers will know how to properly pronounce the text. 


### Head Tags in HTML: 
The ``<head>`` tags contains information that is processed by the machines. Nedested in side of the the tag is the metadata which is the data that describes the document to the machine. 

***Example:***

```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
</head>

```

### UTF-8 Character
The UTF-8 is the the standard character encoding you should use in your web pages. This is one of the first ``<meta>`` tags shown in the ``<head>`` element. Shown in the example above.

> **Tip:** A Unicode-based encoding such as the UTF-8 can support many langauages and can accommodate pages and forms in any mixture of those langauages. 

### Viewport Meta Tag: 
The viewport meta tag renders the width of the page to the width of the device's screen size.  For example if you have a device that is 600px wide then the browser window will be 600px wide. 

The initial-scale controls the zoom level. The value of 1 for the initial-scale prevents the default zoom of the browser. 

***Example:*** 
```
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 ```

 ### X-UA-Compatible: 

 The ``<meta>`` tag specifices the document mode for the Internet Explorer. ``IE=edge`` is the highest supported mode. 

 ***Example:***
 ```
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  ```
### Title Tag
The name says it all the title of the web page. This text is shown on your browser's title bar. 

***Example:*** 
```
<title>HTML 5 Boilerplate</title>

```

### CSS stylesheet: 
This code links to your custom CSS to the HTML. CSS stands for Cascading Style Sheets. This is the code that makes the website asthetically pleasing. ``rel="stylesheet"`` defines the relationship between the HTML file and the external stylesheet. 

***Example:***
```
  <link rel="stylesheet" href="style.css">
  ```

### Script tags in HTML: 

This is the link that will connect it to the JavaScript which is the code behind the scences. This where the clicks, inputs and actions are placed. 

***Example:***
```	<script src="index.js"></script>```

Here are some great refernces that you can take a look at all of what HTML has to offer including the boilerplate. [MDN HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

Reference of the Basic HTML5 template: [HTML Article](https://www.freecodecamp.org/news/basic-html5-template-boilerplate-code-example/)