# Basic HTML

## HTML Introduction
```
HTML = HyperText Markup Language
<TagName>
```
```html
<h1> The Adventures of Sherlock Holmes</h1>
<br>
<h3>by</h3> 
<br>
<h2>Arthur Conan Doyle</h2>
```

## The Anatomy of an HTML Tag
```
<h1>Hello World!</h1>
<h1> is an opening tag, and </h1> is a closing tag and in between is the content
<br> Self-closing tag
<hr size="3">  the "size" part is an attribute
```
```html
<center>
<hr size="3" noshade>
<h1> The Adventures of Sherlock Holmes</h1>
<br>
<h3>by</h3> 
<br>
<h2>Arthur Conan Doyle</h2>
<hr size="3" noshade>
</center>
```

## What is The HTML Boilerplate?
```
<!DOCTYPE html> This tell the version of HTML
<html lang="en"> This tell that everything between <html> and </html> is goin to be HTML code

The HTML code consist basically in a <head> and a <body>
<head> The head is the part of the HTML that contains information about the webpage and it tells the browser hot it should handle the page

Meta tag : Describe meta data within an HTML document
 <head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head> 
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sigifredo's Site</title>
</head>
<body>
    
</body>
</html>
```

## How to structure text in HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sigifredo's Personal Site</title>
</head>
<body>
    <h1>Sigifredo</h1>
    <p><em>Currently <strong>web developer</strong> student</em></p>
    <p>I am currently studying web development. I love chess</p>
    <hr>
    <h3>Education</h3>
</body>
</html>
```

## HTML Lists
```html
    <h3>Front-End Skills</h3>
    <ul>
        <li>HTML intermediate</li>
        <li>CSS intermediate</li>
        <li>Bootstrap intermediate</li>
        <li>JavaScript intermediate</li>
        <li>Document Object Model (DOM)</li>
        <li>jQuery</li>
    </ul>
    <h3>My Hobbies</h3>
    <ol>
        <li>Playing chess</li>
        <li>Writing</li>
        <li>Music</li>
    </ol>
```

## HTML Image Elements
```html
<img src="./image-source" alt="image-description">
```

## HTML Links and Anrchor Tags
```html
<a href="./link-source">Link Text</a>
```

## HTML Tables
```

```
