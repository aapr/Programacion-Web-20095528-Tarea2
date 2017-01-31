# Web Programming
## Today's Agenda (1/31/2017)

### JavaScript
JavaScript (/ˈdʒævəˌskrɪpt/) is a high-level, dynamic, untyped, and interpreted programming language. It has been standardized in the ECMAScript language specification. Alongside HTML and CSS, JavaScript is one of the three core technologies of World Wide Web content production; the majority of websites employ it, and all modern Web browsers support it without the need for plug-ins. JavaScript is prototype-based with first-class functions, making it a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles. It has an API for working with text, arrays, dates and regular expressions, but does not include any I/O, such as networking, storage, or graphics facilities, relying for these upon the host environment in which it is embedded. [Source: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript)]

### DOM
The Document Object Model (DOM) is a cross-platform and language-independent application programming interface that treats an HTML, XHTML, or XML document as a tree structure wherein each node is an object representing a part of the document.

### Document Interface
The Document interface represents any web page loaded in the browser and serves as an entry point into the web page's content, which is the DOM tree. The DOM tree includes elements such as `<body>` and `<table>`, among many others. It provides functionality global to the document, like how to obtain the page's URL and create new elements in the document.

In today's class we will focus on some of the document's interface **[Methods](https://developer.mozilla.org/en-US/docs/Web/API/Document#Methods)**, specifically on the ones used to query the DOM tree.

## Exercises
* Use an element's `childNodes` and `nodeType` to create a program that print's out the DOM tree of an HTML document. Please use indentation rules to ilustrate the tree's depth.
* Download the `aboutme.html` document.
  * Add a script tag to the bottom.
  * Change the body style so it has a font-family of "Arial, sans-serif".
  * Replace each of the spans (nickname, favorites, hometown) with your own information.
  * Iterate through each li and change the class to "listitem". Add a style tag that sets a rule for "listitem" to make the color red.
  * Create a new img element and set its src attribute to a picture of you. Append that element to the page.
* Books
  * Create a webpage with an h1 of "My Book List".
  * Add a script tag to the bottom of the page, where all your JS will go.
  * Copy the following array of books
  
          var books = [
          {title: 'The Design of EveryDay Things',
           author: 'Don Norman',
           alreadyRead: false
          },
          {title: 'The Most Human Human',
          author: 'Brian Christian',
          alreadyRead: true
          }];
  
  * Iterate through the array of books. For each book, create a p element with the book title and author and append it to the page.
  * Use a ul and li to display the books.
  * Add a property to each book with the URL of the book cover, and add an img element for each book on the page.
  * Change the style of the book depending on whether you have read it or not.
* Random
  * Download the `random.html` document and the grid.css style document.
  * Add a script tag to the bottom of the page, where all your JS will go.
  * Read about the **setInterval** function.
  * Within the main `<div>` container, append a 10x10 div grid.
  * Use the **setInterval** function and add code that changes the color of the grid cells randomly every half second.