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
<tr> Table Row
<td> Table Data
Tables also have header, body and footer mirroring what we have for our HTML website
<thead>
<tbody>
<tfoot>
```
```html
    <table border="1">
        <thead>
            <tr>
                <th>Dates</th>
                <th>Work</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>2010-2013</td>
                <td>Lead developer</td>
            </tr>
            <tr>
                <td>2010</td>
                <td>Reasercher at Developer Design</td>
            </tr>

        </tbody>
    </table>
```
![This is an image](/HTML-Tables.png)

## Using HTML Tables for Layout
```html
<table cellspacing="20" >
```

## HTML Tables code challenge
```diff
+create a table where you've got an h3 for the skills subtitle, 
+and then you've got all your skills listed in a column on the left, 
+and on the right you've got some rows where you've listed using emojis to show how familiar you are with each skill ranging from 5 star to 1 star.
```
![Tables-Challenge](https://user-images.githubusercontent.com/93165649/149387413-23ec39bf-0d6f-4ee4-be2e-c5bd828bae95.png)

## HTML Forms
```
<form> We use the form tag to define what should go into our form
<label> Between the opening and closing label tags, you can write some text that will be displayed as a label inside your form.
<input type="text"> You can define the input type by using the type attribute
<input type="text">
<input type="submit">
<input type="file">
<input type="date">
<input type="radio">
<input type="range">
```
```html
    <form class="" action="index.html" method="post">
        <label for="">Your Name:</label>
        <input type="text" name="" id="" value="">
        <input type="color"> <br>
        <input type="password">
        <input type="submit" name="">
        <br>
        <label for="">Do you want to sign up to the email list?</label>
        <input type="checkbox">
    </form>
```

## Forms in practice
```html
    <form action="mailto:info@londonappbrewery.com" method="post" enctype="text/plain">
        <label for="">Your Name:</label>
        <input type="text" name="yourName" id="" value=""><br>
        <label for="">Your Email:</label>
        <input type="email" name="yourEmail"><br>
        <label for="">Your Message:</label><br>
        <textarea name="yourMessage" id="" cols="30" rows="10"></textarea><br>
        <input type="submit" name="">
    </form>
```

## Resources
[i vs em](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em#%3Ci%3E_vs._%3Cem%3E)
 
[b vs strong](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong)
 
[The Anchor element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
 
[The Table element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
 
[The Form element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
 
[The Input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
