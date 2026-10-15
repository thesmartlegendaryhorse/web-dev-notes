# INTRODUCTION

	
- As we all know HTML and CSS are 2 main languages that work together to make everything we see when we look at something on the web, HTMLis the raw data that a webpage is built out of kind of like the human body, CSS is what makes it look pretty kind of like our clothes.

- Alot of other sources everywhere consider HTML and CSS as programming languages but its not all true because their task is to present information not to program any logic (you cant make a calculator with HTML and CSS for example).

- JavaScript on the other hand is a programming language that we will learn soon is what makes web pages do things kind of like the nervous system of the human body.

-Still theres a ton of thing you can do with HTML and CSS alone and you will defenitly need them both.

  
# Elements and Tags

## introduction 

- HTML (HyperText Markup Language) defines the structure of webpages, we use it to create all of the paragraphes, headings, lists, images, and links that make up a typical webpage. 

## Elements and tags 

- Almost all elements on an HTML page are pieces of content inside opening and closing HTML tags 

- HTML tags are essential building blocks that define the structure and content of a webpage, opening tags tell the browser this is the start of an HTML element, they are made of a keyword inside angle brackets <>, for example paragraph tag looks like this : <p>

- Closing tags tell the browser where that element ends, for example </p>

a paragraph element looks like this :

    <p>something soemthing 6767676767</p>


- HTML has a vast list of predefined tags that we use to create all kinds of different elements, it is important to use the correct tags for content, using the correct tags can have a big impact on : how they are ranked in search engines and how ccessible they are to users who rely on assistive technologies, like screen readers, to use the internet.

- Using the correct elements for content is called semantic HTML.

## Void Elements
 
- some HTML elements do not have a closing tag, which means they only have 1 tag like : <br> or <img> known as void elements because they void of any content



# HTML Boilerplate 

## Introduction 

 - All HTML documets have the same basic structure or boilerplate that needs to be in place before anything is done yet.

## Creating an HTML file


- it is easy to make a html file just add a .html at the end like or example index.html while it doesnt matter what name it got but when making a website for it t obe deployed we need to name the html file as index because web servers will look for an index.html when landing on our website otherwise we will face big problems.

## The DOCTYPE


 - every html page starts with a doctype declaration because its purpose is to tell the browser which version of HTML it has to use to render the document, the latest html version is html 5 and its doctype is <!DOCTYPE html>, the doctype for html4 for example was <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">


## HTML element

- after giving the doctype we have to provide an <html> element known as the root element of the document, meaning that every other element in the document will be a descendent of it, that is more important for later when we learn about manipulating html with javascript but for now just know that <html> should be in every html document

## Head element

- the <head> element is where we put information about our webpage and we should not put any element that displays content on the webpage.

- now in that head element we use the <meta> element which is important because it ensures that the webpage will display special symbols ad characters from different languages correctly 
- the <title> element is used to give the webpage a human friendly title displayed on the browser tab


## Body element 


- the <body> elemnt is where all the content will be displayed to users will go like text and images and lists and links etc.

- now when opening a blank .html file in vscode we can just type ! in the first line and we press enter a "template" will appear like this :
```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Document</title>
</head>
<body>
</body>
</html>
```

- note that the line <meta name="viewport" content="width=device-width, initial-scale=1.0"> has not been explained yet and will be introduced in a later topic.

# Working with text

  - Most text on the internet is text based, so we will work with html text elements quite alot  



## Paragraphs

- if we write something inside the body  just plainly like this :

```html
<html>
  <head>
  </head>
  <body>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua.

    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
  nisi ut aliquip ex ea commodo consequat.
  </body>   
 </html>

- our resualt will be : 
 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
 
- because when the browser finds new lines in your html it will compress them down into a single chunk of space, so if we want the text to be a paragraph we will have to use the ```<p></p>``` tag which looks like this :
```html
<html>
  <head>
  </head>
  <body>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua.</p>

    <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
  nisi ut aliquip ex ea commodo consequat.</p>
  </body>   
 </html>```

- will give us the desired resault : 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.


## Headings

- Headings are some kind of different HTML text element because they are displayed larger and bolder than other text to signal that they are headings.

- and with that there are 6 levels of headings starting from <h1> to <h6> with h1 beaing largest and h6 tiniest, for example this code :

```html
<html>
  <head>
  </head>
  <body>
    <h1>This is a heading 1</h1>
    <h2>This is a heading 2</h2>
    <h3>This is a heading 3</h3>
    <h4>This is a heading 4</h4>
    <h5>This is a heading 5</h5>
    <h6>This is a heading 6</h6>
  </body>
 </html>
```
- it will look like that :

<html>
  <head>
  </head>
  <body>
    <h1>This is a heading 1</h1>
    <h2>This is a heading 2</h2>
    <h3>This is a heading 3</h3>
    <h4>This is a heading 4</h4>
    <h5>This is a heading 5</h5>
    <h6>This is a heading 6</h6>
  </body>
 </html>



