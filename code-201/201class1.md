*MOHAMMED ABUBAKAR*

# CLASS 201 READING NOTES 1

## HTTP 
- The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client 

## PARSED
- The browser parses the HTML file first, and that leads to the browser recognizing any link element references to external CSS stylesheets and any script element references to scripts.
  
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
  
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
  
- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
  
## IMAGES
  
- When you find the image you want, click on the image to get an enlarged view of it.

- Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.
  
## Strings
- This is a sequence of text known as a string. To signify that the value is a string, enclose it in single or double quote marks.
  
*EXAMPLE* 
  
  let myVariable = 'Bob'; or
  
  let myVariable = "Bob";
  
## Number
  - This is a number. Numbers don't have quotes around them.
  
*EXAMPLE*
  
  let myVariable = 10;
  
## METADATA
  
  - tells search engines how to read and display sites on search engine result pages (SERPs)
  
  - <meta> defines metadata about an HTML document. <meta> tags always go inside the <head> element, and are typically used to specify character set, page 
  
    description, keywords, author of the document, and viewport settings.
  
## How to Start a Website
  
  - First step of creating a website is creating the html.
  
  - One of the most important steps is identifying your ideal audience and anticipated visitors by demographic data, tech-savviness, intent, personal goals 
    
    and pain point, the stage of their purchase decision making, and more.
  
## Semantics
  
  - < h1 > < span > … < / span > < / h1 > < !-- This is fine -- >
  
    < div > < h1 > … < / h1 > < / div >   < !-- This is fine -- >
  
    < h1 > < span > … < /h1 > < /span > < !-- This is wrong -- >
  
    < span > < h1 > … < /h1 > < /span > < !-- This is wrong -- >
  
  - An span is an inline element
  
  - An h1 is a block element
  
  - An inline element cannot contain a block element

  - Elements cannot be partially contained by other elements
      
  - semantic HTML tags help the search engines and other user devices to determine the importance and context of web pages.
      
      ## Things i ant to know
      
      With Jss, when do we get to make things jump out the screen.
  

  
