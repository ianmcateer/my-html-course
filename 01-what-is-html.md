# What is HTML?

HTML is the standard markup language for the web. 

With HTML you can create your own website. 

- It stands for Hypertext markup language
- HTML desrcibes the structure of your web page


## Simple HTML Document
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Page Title</title>
    </head>
    <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
    </body>
</html>
```

```
The <!DOCTYPE html> declaration defines this document to be HTML5
```
In HTML the DOCTYPE is the required in all documents. 
This declaration tells the browser what type of document to expect so that the browser can correctly determine how to parse and render your HTML. If you forget to include it browser will go into quirks mode which is designed for supporting old web browsers. You basically dont want your browser to parse your HTML in this mode. You want it to follow the standards mode which it will do if you include the correct DOCTYPE declaration. Here im declaring my document type to be html

```
The <html> element is the root element of an HTML page
```
This html element is the container for all other elements on our web page. 

A html element consists of a start tag and an end tag, with content nested in between them
```
<tagname>Content goes here...</tagname>
```
Some elements don't have a closing tag like the ```<br>``` element

```
The <head> element contains meta information about the document
```
Now the head of a document is the part that is not displayed in the web browser when the page is loaded. The head contains information such as the title of our document, its where we include any scripts we want to run and any css styles we want applied. In here we can also link to any external javascript or css files we may want to use.

```
 <meta charset="utf-8">
```
This charset stands for character set. We are settig it to utf-8 which is capable of encoding all characters on the web. Long story short: leave it in

```
The <title> element specifies a title for the document
```
This element lives in the head. This defines a title which you can see in the browser tab and is required in all html documents. Search engines also use this.

```
The <body> element contains the visible page content
```
The body element comes after the head  and contains the viible page content that you see.

```
The <h1> element defines a large heading
```

```
The <p> element defines a paragraph
```

## Structure Visualisation 
![picture](./images/html-structure.png)