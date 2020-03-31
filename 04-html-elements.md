# HTML Elements

Elements are components of a document written in HTML. 

A HTML element consists of a start tag and an end tag, with the content inserted in between them.

```
<tagname>Content goes here...</tagname>
```

We have seen these already, ```<html></html>``` is an example of an element. 

## Difference bwteen an element and a tag
So the HTML element includes the tag and content between the tag.
The Tags are just part of the HTML syntax.

## Nested HTML elements
Elements can be nested(elements can contain other elements). We have seen this already as well. 

```
<body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
</body>
```

Here the body element contains two elements, we call these two elements children elements. 

## Some Elemenents do not need a closing tag
A standard HTML element has content encolsed within the opening and closing tags. But some elements can be empty. Liek the ```<img>``` element. These elements are usually used to add or embed content into documents. 

```
<area>	<base>	<br>	<col>	<embed>
<hr>	<img>	<input>	<keygen> <link>
<meta>	<param>	<source> <track>	<wbr>
```

HTML5 does not require empty elements to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.

## HTML is not case sensitive
This means HTML does not care if you use capital or lower case ```<P>``` means the same as ```<p>```.

But its recommended to always use lowercase.

## Most common HTML elements 

```
<h1>
<p>
<div>
```