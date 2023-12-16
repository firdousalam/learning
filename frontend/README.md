# HTML
HTML stands for HyperText Markup Language. It is used to design the web pages. With the help of HTML, you can create a complete website structure. HTML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages and markup language defines the text document within the tag that define the structure of web pages. This HTML Tutorial is designed to provide basic to advanced HTML concepts for beginners and professionals both.



# HTML Basic Structure of Web Page
The basic structure of an HTML page is laid out below. It contains the essential building-block elements (i.e. doctype declaration, HTML, head, title, and body elements) upon which all web pages are created.


# HTML Basic Tags
```<DOCTYPE! html>``` – A doctype or document type declaration is an instruction that tells the web browser about the markup language in which the current page is written. It is not an element or tag. The doctype declaration is not case-sensitive.
he HTML Document Type
All HTML documents must start with a <!DOCTYPE> declaration.

The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.

In HTML5, the <!DOCTYPE> declaration is simple:

```<!DOCTYPE html>```
In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).

```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">

```


```<html> ```– This tag is used to define the root element of HTML document. This tag tells the browser that it is an HTML document. It is the second outer container element that contains all other elements within it.


```<head> ```– This tag is used to define the head portion of the HTML document that contains information related to the document. Elements within the head tag are not visible on the front-end of a webpage.

```<body>``` – The body tag is used to enclose all the visible content of a webpage. In other words, the body content is what the browser will show on the front end.

Example: This is the basic example of HTML that display the heading and paragraph content.

```
<!DOCTYPE html> 
<html> 
  
<!-- Head Section content -->
<head> 
  
    <!-- Page title -->
    <title>Basic Web Page</title> 
</head> 
  
<!-- Body Section content -->
<body> 
  
    <!-- Used to display heading content -->
    <h1>Welcome to MERN STACK TUTORIALS</h1> 
  
    <!-- Used to display paragrapg content -->
    <p>BY TECHNOPHILE FIRDOUS</p> 
</body> 
  
</html> 
```
# ISO Language Codes
You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers:

<html lang="en">
...
</html>
In XHTML, the language is declared inside the <html> tag as follows:

<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
...
</html>


# How the HTML code compile? 
Html is a markup language. I.e, you are just defining how things are displayed, you cannot actually perfom any mathematical operations.
And yes, browsers do contain something similar to a compiler ( called parser) which will identify the various tags and display them accordingly. What the browser does is search for various tags in the html file, the way to display the tags is written iside the browser code, which it follows and prints the text/image or whatever you have used.
HTML is not a programming language.

It is neither compiled nor interpreted.

HTML is what’s known as a “markup language.” That’s to say, it represents, not a program, but some data.

Javascript, which is often included with HTML, inside a “script” tag, has traditionally been interpreted (if on a normal webpage), but there are fancier situations in which you can compile it

# Element Content
The content of an HTML element is the information between the opening and closing tags of an element.
```
<h1>Codecademy is awesome! 🙂</h1>
<li> List Item Element
The <li> list item element create list items inside:

Ordered lists <ol>
Unordered lists <ul>
<ol>
  <li>Head east on Prince St</li>
  <li>Turn left on Elizabeth</li>
</ol>

<ul>
  <li>Cookies</li>
  <li>Milk</li>
</ul>
```


# Basic HTML
```
Tag	Description
<!DOCTYPE> 	Defines the document type
<html>	Defines an HTML document
<head>	Contains metadata/information for the document
<title>	Defines a title for the document
<body>	Defines the document's body
<h1> to <h6>	Defines HTML headings
<p>	Defines a paragraph
<br>	Inserts a single line break
<hr>	Defines a thematic change in the content
<!--...-->	Defines a comment
# Formatting
Tag	Description
<acronym>	Not supported in HTML5. Use <abbr> instead.
Defines an acronym
<abbr>	Defines an abbreviation or an acronym
<address>	Defines contact information for the author/owner of a document/article
<b>	Defines bold text
<bdi>	Isolates a part of text that might be formatted in a different direction from other text outside it
<bdo>	Overrides the current text direction
<big>	Not supported in HTML5. Use CSS instead.
Defines big text
<blockquote>	Defines a section that is quoted from another source
<center>	Not supported in HTML5. Use CSS instead.
Defines centered text
<cite>	Defines the title of a work
<code>	Defines a piece of computer code
<del>	Defines text that has been deleted from a document
<dfn>	Specifies a term that is going to be defined within the content
<em>	Defines emphasized text 
<font>	Not supported in HTML5. Use CSS instead.
Defines font, color, and size for text
<i>	Defines a part of text in an alternate voice or mood
<ins>	Defines a text that has been inserted into a document
<kbd>	Defines keyboard input
<mark>	Defines marked/highlighted text
<meter>	Defines a scalar measurement within a known range (a gauge)
<pre>	Defines preformatted text
<progress>	Represents the progress of a task
<q>	Defines a short quotation
<rp>	Defines what to show in browsers that do not support ruby annotations
<rt>	Defines an explanation/pronunciation of characters (for East Asian typography)
<ruby>	Defines a ruby annotation (for East Asian typography)
<s>	Defines text that is no longer correct
<samp>	Defines sample output from a computer program
<small>	Defines smaller text
<strike>	Not supported in HTML5. Use <del> or <s> instead.
Defines strikethrough text
<strong>	Defines important text
<sub>	Defines subscripted text
<sup>	Defines superscripted text
<template>	Defines a container for content that should be hidden when the page loads
<time>	Defines a specific time (or datetime)
<tt>	Not supported in HTML5. Use CSS instead.
Defines teletype text
<u>	Defines some text that is unarticulated and styled differently from normal text
<var>	Defines a variable
<wbr>	Defines a possible line-break

# Forms and Input
Tag	Description
<form>	Defines an HTML form for user input
<input>	Defines an input control
<textarea>	Defines a multiline input control (text area)
<button>	Defines a clickable button
<select>	Defines a drop-down list
<optgroup>	Defines a group of related options in a drop-down list
<option>	Defines an option in a drop-down list
<label>	Defines a label for an <input> element
<fieldset>	Groups related elements in a form
<legend>	Defines a caption for a <fieldset> element
<datalist>	Specifies a list of pre-defined options for input controls
<output>	Defines the result of a calculation
# Frames
Tag	Description
<frame>	Not supported in HTML5.
Defines a window (a frame) in a frameset
<frameset>	Not supported in HTML5.
Defines a set of frames
<noframes>	Not supported in HTML5.
Defines an alternate content for users that do not support frames
<iframe>	Defines an inline frame

# Images
Tag	Description
<img>	Defines an image
<map>	Defines a client-side image map
<area>	Defines an area inside an image map
<canvas>	Used to draw graphics, on the fly, via scripting (usually JavaScript)
<figcaption>	Defines a caption for a <figure> element
<figure>	Specifies self-contained content
<picture>	Defines a container for multiple image resources
<svg>	Defines a container for SVG graphics

# Audio / Video
Tag	Description
<audio>	Defines sound content
<source>	Defines multiple media resources for media elements (<video>, <audio> and <picture>)
<track>	Defines text tracks for media elements (<video> and <audio>)
<video>	Defines a video or movie

# Links
Tag	Description
<a>	Defines a hyperlink
<link>	Defines the relationship between a document and an external resource (most used to link to style sheets)
<nav>	Defines navigation links

#Lists
Tag	Description
<menu>	Defines an alternative unordered list
<ul>	Defines an unordered list
<ol>	Defines an ordered list
<li>	Defines a list item
<dir>	Not supported in HTML5. Use <ul> instead.
Defines a directory list
<dl>	Defines a description list
<dt>	Defines a term/name in a description list
<dd>	Defines a description of a term/name in a description list

# Tables
Tag	Description
<table>	Defines a table
<caption>	Defines a table caption
<th>	Defines a header cell in a table
<tr>	Defines a row in a table
<td>	Defines a cell in a table
<thead>	Groups the header content in a table
<tbody>	Groups the body content in a table
<tfoot>	Groups the footer content in a table
<col>	Specifies column properties for each column within a <colgroup> element
<colgroup>	Specifies a group of one or more columns in a table for formatting

#Styles and Semantics
Tag	Description
<style>	Defines style information for a document
<div>	Defines a section in a document
<span>	Defines a section in a document
<header>	Defines a header for a document or section
<hgroup>	Defines a header and related content
<footer>	Defines a footer for a document or section
<main>	Specifies the main content of a document
<section>	Defines a section in a document
<search>	Defines a search section
<article>	Defines an article
<aside>	Defines content aside from the page content
<details>	Defines additional details that the user can view or hide
<dialog>	Defines a dialog box or window
<summary>	Defines a visible heading for a <details> element
<data>	Adds a machine-readable translation of a given content

# Meta Info
Tag	Description
<head>	Defines information about the document
<meta>	Defines metadata about an HTML document
<base>	Specifies the base URL/target for all relative URLs in a document
<basefont>	Not supported in HTML5. Use CSS instead.
Specifies a default color, size, and font for all text in a document

#Programming
Tag	Description
<script>	Defines a client-side script
<noscript>	Defines an alternate content for users that do not support client-side scripts
<applet>	Not supported in HTML5. Use <embed> or <object> instead.
Defines an embedded applet
<embed>	Defines a container for an external (non-HTML) application
<object>	Defines an embedded object
<param>	Defines a parameter for an object


   ```




# Video Element ```<video>```

The ```<video>``` element embeds a media player for video playback. The src attribute will contain the URL to the video. Adding the controls attribute will display video controls in the media player.

Note: The content inside the opening and closing tag is shown as a fallback in browsers that don’t support the element.
```
<video src="test-video.mp4" controls>
  Video not supported
</video>
```

# Emphasis Element``` <em>```
The ```<em>``` element emphasizes text and browsers will usually italicize the emphasized text by default.
```
<p>This <em>word</em> will be emphasized in italics.</p>
```
# ```<ol>``` Ordered List Element
The ```<ol>``` ordered list element creates a list of items in sequential order. Each list item appears numbered by default.
```
<ol>
  <li>Preheat oven to 325 F 👩‍🍳</li>
  <li>Drop cookie dough 🍪</li>
  <li>Bake for 15 min ⏰</li>
</ol>
```
# ```<div>``` Div Element
The ```<div>``` element is used as a container that divides an HTML document into sections and is short for “division”. ```<div>``` elements can contain flow content such as headings, paragraphs, links, images, etc.
```
<div>
  <h1>A section of grouped elements</h1>
  <p>Here’s some text for the section</p>
</div>
<div>
  <h1>Second section of grouped elements</h1>
  <p>Here’s some text</p>
</div>
```
# HTML Structure
HTML is organized into a family tree structure. HTML elements can have parents, grandparents, siblings, children, grandchildren, etc.
```
<body>
  <div>
    <h1>It's div's child and body's grandchild</h1>
    <h2>It's h1's sibling</h2>
  </div>
</body>
```
# Closing Tag
An HTML closing tag is used to denote the end of an HTML element. The syntax for a closing tag is a left angle bracket < followed by a forward slash / then the element name and a right angle bracket to close >.
```
<body>
  ...
</body>
```

# Attribute Name and Values
HTML attributes consist of a name and a value using the following syntax: name="value" and can be added to the opening tag of an HTML element to configure or change the behavior of the element.
```
<elementName name="value"></elementName>
```

# ```<br>``` Line Break Element
The ```<br>``` line break element will create a line break in text and is especially useful where a division of text is required, like in a postal address. The line break element requires only an opening tag and must not have a closing tag.
```
A line break haiku.<br>
Poems are a great use case.<br>
Oh joy! A line break.
```
# ```<img>``` Image Element
HTML image ```<img>``` elements embed images in documents. The src attribute contains the image URL and is mandatory. ```<img>``` is an empty element meaning it should not have a closing tag.
```
<img src="image.png">
```
# ```<h1>-<h6>``` Heading Elements
HTML can use six different levels of heading elements. The heading elements are ordered from the highest level ```<h1>``` to the lowest level ```<h6>```.
```
<h1>Breaking News</h1>
<h2>This is the 1st subheading</h2>
<h3>This is the 2nd subheading</h3>

<h6>This is the 5th subheading</h6>
<p> Paragraph Element
The <p> paragraph element contains and displays a block of text.

<p>This is a block of text! Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
```

# Unique ID Attributes
In HTML, specific and unique id attributes can be assigned to different elements in order to differentiate between them.

When needed, the id value can be called upon by CSS and JavaScript to manipulate, format, and perform specific instructions on that element and that element only. Valid id attributes should begin with a letter and should only contain letters (a-Z), digits (0-9), hyphens (-), underscores (_), and periods (.).
```
<h1 id="A1">Hello World</h1>
```

# HTML Attributes
HTML attributes are values added to the opening tag of an element to configure the element or change the element’s default behavior. In the provided example, we are giving the ```<p> ``` (paragraph) element a unique identifier using the id attribute and changing the color of the default text using the style attribute.
```
<p id="my-paragraph" style="color: green;">Here’s some text for a paragraph that is being altered by HTML attributes</p>
```
# ```<ul>``` Unordered List Element
The ```<ul>``` unordered list element is used to create a list of items in no particular order. Each individual list item will have a bullet point by default.

```
<ul>
  <li>Play more music 🎸</li>
  <li>Read more books 📚</li>
</ul>
```
# alt Attribute
An ```<img>``` element can have alternative text via the alt attribute. The alternative text will be displayed if an image fails to render due to an incorrect URL, if the image format is not supported by the browser, if the image is blocked from being displayed, or if the image has not been received from the URL.

The text will be read aloud if screen reading software is used and helps support visually impaired users by providing a text descriptor for the image content on a webpage.
```
<img src="path/to/image" alt="text describing image" />
```

# ```<body>``` Body Element
The ```<body>``` element represents the content of an HTML document. Content inside ```<body>``` tags are rendered on the web browsers.

Note: There can be only one ```<body>``` element in a document.

```
<body>
  <h1>Learn to code with Codecademy :)</h1>
</body>
```

# Span Element
The ```<span>``` element is an inline container for text and can be used to group text for styling purposes. However, as ```<span>``` is a generic container to separate pieces of text from a larger body of text, its use should be avoided if a more semantic element is available.
```
<p><span>This text</span> may be styled differently than the surrounding text.</p>
<strong> Strong Element
The <strong> element highlights important, serious, or urgent text and browsers will normally render this highlighted text in bold by default.

<p>This is <strong>important</strong> text!</p>
```

# HTML Element
An HTML element is a piece of content in an HTML document and uses the following syntax: opening tag + content + closing tag. In the code provided:
```
<p> is the opening tag.
Hello World! is the content.
</p> is the closing tag.
<p>Hello World!</p>
```

# HTML Tag
The syntax for a single HTML tag is an opening angle bracket < followed by the element name and a closing angle bracket >. Here is an example of an opening ```<div>``` tag.

# ```<sub> and <sup>```
Subscriptssub and superscriptssup with ```<sub> and <sup>```.


```
Tag	Description
<!--...-->	Defines a comment
<!DOCTYPE> 	Defines the document type
<a>	Defines a hyperlink
<abbr>	Defines an abbreviation or an acronym
<acronym>	Not supported in HTML5. Use <abbr> instead.
Defines an acronym
<address>	Defines contact information for the author/owner of a document
<applet>	Not supported in HTML5. Use <embed> or <object> instead.
Defines an embedded applet
<area>	Defines an area inside an image map
<article>	Defines an article
<aside>	Defines content aside from the page content
<audio>	Defines embedded sound content
<b>	Defines bold text
<base>	Specifies the base URL/target for all relative URLs in a document
<basefont>	Not supported in HTML5. Use CSS instead.
Specifies a default color, size, and font for all text in a document
<bdi>	Isolates a part of text that might be formatted in a different direction from other text outside it
<bdo>	Overrides the current text direction
<big>	Not supported in HTML5. Use CSS instead.
Defines big text
<blockquote>	Defines a section that is quoted from another source
<body>	Defines the document's body
<br>	Defines a single line break
<button>	Defines a clickable button
<canvas>	Used to draw graphics, on the fly, via scripting (usually JavaScript)
<caption>	Defines a table caption
<center>	Not supported in HTML5. Use CSS instead.
Defines centered text
<cite>	Defines the title of a work
<code>	Defines a piece of computer code
<col>	Specifies column properties for each column within a <colgroup> element 
<colgroup>	Specifies a group of one or more columns in a table for formatting
<data>	Adds a machine-readable translation of a given content
<datalist>	Specifies a list of pre-defined options for input controls
<dd>	Defines a description/value of a term in a description list
<del>	Defines text that has been deleted from a document
<details>	Defines additional details that the user can view or hide
<dfn>	Specifies a term that is going to be defined within the content
<dialog>	Defines a dialog box or window
<dir>	Not supported in HTML5. Use <ul> instead.
Defines a directory list
<div>	Defines a section in a document
<dl>	Defines a description list
<dt>	Defines a term/name in a description list
<em>	Defines emphasized text 
<embed>	Defines a container for an external application
<fieldset>	Groups related elements in a form
<figcaption>	Defines a caption for a <figure> element
<figure>	Specifies self-contained content
<font>	Not supported in HTML5. Use CSS instead.
Defines font, color, and size for text
<footer>	Defines a footer for a document or section
<form>	Defines an HTML form for user input
<frame>	Not supported in HTML5.
Defines a window (a frame) in a frameset
<frameset>	Not supported in HTML5.
Defines a set of frames
<h1> to <h6>	Defines HTML headings
<head>	Contains metadata/information for the document
<header>	Defines a header for a document or section
<hgroup>	Defines a header and related content
<hr>	Defines a thematic change in the content
<html>	Defines the root of an HTML document
<i>	Defines a part of text in an alternate voice or mood
<iframe>	Defines an inline frame
<img>	Defines an image
<input>	Defines an input control
<ins>	Defines a text that has been inserted into a document
<kbd>	Defines keyboard input
<label>	Defines a label for an <input> element
<legend>	Defines a caption for a <fieldset> element
<li>	Defines a list item
<link>	Defines the relationship between a document and an external resource (most used to link to style sheets)
<main>	Specifies the main content of a document
<map>	Defines an image map
<mark>	Defines marked/highlighted text
<menu>	Defines an unordered list
<meta>	Defines metadata about an HTML document
<meter>	Defines a scalar measurement within a known range (a gauge)
<nav>	Defines navigation links
<noframes>	Not supported in HTML5.
Defines an alternate content for users that do not support frames
<noscript>	Defines an alternate content for users that do not support client-side scripts
<object>	Defines a container for an external application
<ol>	Defines an ordered list
<optgroup>	Defines a group of related options in a drop-down list
<option>	Defines an option in a drop-down list
<output>	Defines the result of a calculation
<p>	Defines a paragraph
<param>	Defines a parameter for an object
<picture>	Defines a container for multiple image resources
<pre>	Defines preformatted text
<progress>	Represents the progress of a task
<q>	Defines a short quotation
<rp>	Defines what to show in browsers that do not support ruby annotations
<rt>	Defines an explanation/pronunciation of characters (for East Asian typography)
<ruby>	Defines a ruby annotation (for East Asian typography)
<s>	Defines text that is no longer correct
<samp>	Defines sample output from a computer program
<script>	Defines a client-side script
<search>	Defines a search section
<section>	Defines a section in a document
<select>	Defines a drop-down list
<small>	Defines smaller text
<source>	Defines multiple media resources for media elements (<video> and <audio>)
<span>	Defines a section in a document
<strike>	Not supported in HTML5. Use <del> or <s> instead.
Defines strikethrough text
<strong>	Defines important text
<style>	Defines style information for a document
<sub>	Defines subscripted text
<summary>	Defines a visible heading for a <details> element
<sup>	Defines superscripted text
<svg>	Defines a container for SVG graphics
<table>	Defines a table
<tbody>	Groups the body content in a table
<td>	Defines a cell in a table
<template>	Defines a container for content that should be hidden when the page loads
<textarea>	Defines a multiline input control (text area)
<tfoot>	Groups the footer content in a table
<th>	Defines a header cell in a table
<thead>	Groups the header content in a table
<time>	Defines a specific time (or datetime)
<title>	Defines a title for the document
<tr>	Defines a row in a table
<track>	Defines text tracks for media elements (<video> and <audio>)
<tt>	Not supported in HTML5. Use CSS instead.
Defines teletype text
<u>	Defines some text that is unarticulated and styled differently from normal text
<ul>	Defines an unordered list
<var>	Defines a variable
<video>	Defines embedded video content
<wbr>	Defines a possible line-break

ADVERTISEMENT

Get Certified
COLOR PICKER
colorpicker
   
```



# What is the DOM?
DOM stands for Document Object Model. It's the interface between JavaScript and the web browser.

With the help of the DOM, you can write JavaScript to create, modify, and delete HTML elements, set styles, classes and attributes, and listen and respond to events.

The DOM tree is generated from an HTML document, which you can then interact with. The DOM is a very complex API which has methods and properties to interact with the DOM tree.


# How the DOM Works – Behind the Scenes
The DOM is organized in a really clever manner. The parent element is called the EventTarget. You can understand better how it works with the help of the below diagram:

DOM-behind-the-scene-1
The EventTarget interface is implemented by objects which can receive events and may have listeners for them. In other words, any target of events implements the three methods associated with this interface. Element, and its children, as well as Document and Window are the most common event targets, but other objects can be event targets, too.

Window represents the browser's window. All global JavaScript objects, functions, and variables automatically become members of the window object. Global variables are properties of the window object. Global functions are methods of the window object. Even the document object (of the HTML DOM) is a property of the window object.

window.document.getElementById("header");

// Both are same

document.getElementById("header");
Nodes are in the DOM aka Document Object model. In the DOM, all parts of the document, such as elements, attributes, text, and so on are organized in a hierarchical tree-like structure that consists of parents and children. These individual parts of the document are known as nodes.

The Node in the above diagram is represented by a JavaScript object. We mostly work with the document which has most commonly used methods like document.queryselector(), document.getElementBy Id(), and so on.

Now we will take a look at the document.

# How to Select, Create, and Delete Elements Using the DOM
With the help of the DOM, we can select, delete, and create element in JavaScript.

How to Select Elements
There are multiple ways we can select HTML elements in JavaScript. These are the methods we'll look at here:

document.getElementById();
document.getElementByClassName();
document.getElementByTagName();
document.querySelector();
document.querySelectorAll();
How to use the document.getElementById() method
The getElementById() method returns an element whose id matches a passed string. Since the ids of HTML elements are supposed to be unique, this is a faster way to select an element with ids.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
