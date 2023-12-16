# HTML
HTML stands for HyperText Markup Language. It is used to design the web pages. With the help of HTML, you can create a complete website structure. HTML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages and markup language defines the text document within the tag that define the structure of web pages. This HTML Tutorial is designed to provide basic to advanced HTML concepts for beginners and professionals both.



# HTML Basic Structure of Web Page
The basic structure of an HTML page is laid out below. It contains the essential building-block elements (i.e. doctype declaration, HTML, head, title, and body elements) upon which all web pages are created.


# HTML Basic Tags
<DOCTYPE! html> – A doctype or document type declaration is an instruction that tells the web browser about the markup language in which the current page is written. It is not an element or tag. The doctype declaration is not case-sensitive.

<html> – This tag is used to define the root element of HTML document. This tag tells the browser that it is an HTML document. It is the second outer container element that contains all other elements within it.


<head> – This tag is used to define the head portion of the HTML document that contains information related to the document. Elements within the head tag are not visible on the front-end of a webpage.

<body> – The body tag is used to enclose all the visible content of a webpage. In other words, the body content is what the browser will show on the front end.

Example: This is the basic example of HTML that display the heading and paragraph content.


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

# How the HTML code compile? 
Html is a markup language. I.e, you are just defining how things are displayed, you cannot actually perfom any mathematical operations.
And yes, browsers do contain something similar to a compiler ( called parser) which will identify the various tags and display them accordingly. What the browser does is search for various tags in the html file, the way to display the tags is written iside the browser code, which it follows and prints the text/image or whatever you have used.
HTML is not a programming language.

It is neither compiled nor interpreted.

HTML is what’s known as a “markup language.” That’s to say, it represents, not a program, but some data.

Javascript, which is often included with HTML, inside a “script” tag, has traditionally been interpreted (if on a normal webpage), but there are fancier situations in which you can compile it

# Element Content
The content of an HTML element is the information between the opening and closing tags of an element.

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
#  Video Element <video>
The <video> element embeds a media player for video playback. The src attribute will contain the URL to the video. Adding the controls attribute will display video controls in the media player.

Note: The content inside the opening and closing tag is shown as a fallback in browsers that don’t support the element.

<video src="test-video.mp4" controls>
  Video not supported
</video>
# Emphasis Element <em>
The <em> element emphasizes text and browsers will usually italicize the emphasized text by default.

<p>This <em>word</em> will be emphasized in italics.</p>
# <ol> Ordered List Element
The <ol> ordered list element creates a list of items in sequential order. Each list item appears numbered by default.

<ol>
  <li>Preheat oven to 325 F 👩‍🍳</li>
  <li>Drop cookie dough 🍪</li>
  <li>Bake for 15 min ⏰</li>
</ol>
# <div> Div Element
The <div> element is used as a container that divides an HTML document into sections and is short for “division”. <div> elements can contain flow content such as headings, paragraphs, links, images, etc.

<div>
  <h1>A section of grouped elements</h1>
  <p>Here’s some text for the section</p>
</div>
<div>
  <h1>Second section of grouped elements</h1>
  <p>Here’s some text</p>
</div>
# HTML Structure
HTML is organized into a family tree structure. HTML elements can have parents, grandparents, siblings, children, grandchildren, etc.

<body>
  <div>
    <h1>It's div's child and body's grandchild</h1>
    <h2>It's h1's sibling</h2>
  </div>
</body>
# Closing Tag
An HTML closing tag is used to denote the end of an HTML element. The syntax for a closing tag is a left angle bracket < followed by a forward slash / then the element name and a right angle bracket to close >.

<body>
  ...
</body>
# Attribute Name and Values
HTML attributes consist of a name and a value using the following syntax: name="value" and can be added to the opening tag of an HTML element to configure or change the behavior of the element.

<elementName name="value"></elementName>
# <br> Line Break Element
The <br> line break element will create a line break in text and is especially useful where a division of text is required, like in a postal address. The line break element requires only an opening tag and must not have a closing tag.

A line break haiku.<br>
Poems are a great use case.<br>
Oh joy! A line break.
# <img> Image Element
HTML image <img> elements embed images in documents. The src attribute contains the image URL and is mandatory. <img> is an empty element meaning it should not have a closing tag.

<img src="image.png">
# <h1>-<h6> Heading Elements
HTML can use six different levels of heading elements. The heading elements are ordered from the highest level <h1> to the lowest level <h6>.

<h1>Breaking News</h1>
<h2>This is the 1st subheading</h2>
<h3>This is the 2nd subheading</h3>
...
<h6>This is the 5th subheading</h6>
<p> Paragraph Element
The <p> paragraph element contains and displays a block of text.

<p>This is a block of text! Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
# Unique ID Attributes
In HTML, specific and unique id attributes can be assigned to different elements in order to differentiate between them.

When needed, the id value can be called upon by CSS and JavaScript to manipulate, format, and perform specific instructions on that element and that element only. Valid id attributes should begin with a letter and should only contain letters (a-Z), digits (0-9), hyphens (-), underscores (_), and periods (.).

<h1 id="A1">Hello World</h1>
# HTML Attributes
HTML attributes are values added to the opening tag of an element to configure the element or change the element’s default behavior. In the provided example, we are giving the <p> (paragraph) element a unique identifier using the id attribute and changing the color of the default text using the style attribute.

<p id="my-paragraph" style="color: green;">Here’s some text for a paragraph that is being altered by HTML attributes</p>
# <ul> Unordered List Element
The <ul> unordered list element is used to create a list of items in no particular order. Each individual list item will have a bullet point by default.

<ul>
  <li>Play more music 🎸</li>
  <li>Read more books 📚</li>
</ul>
# alt Attribute
An <img> element can have alternative text via the alt attribute. The alternative text will be displayed if an image fails to render due to an incorrect URL, if the image format is not supported by the browser, if the image is blocked from being displayed, or if the image has not been received from the URL.

The text will be read aloud if screen reading software is used and helps support visually impaired users by providing a text descriptor for the image content on a webpage.

<img src="path/to/image" alt="text describing image" />
# <body> Body Element
The <body> element represents the content of an HTML document. Content inside <body> tags are rendered on the web browsers.

Note: There can be only one <body> element in a document.

<body>
  <h1>Learn to code with Codecademy :)</h1>
</body>
# <span> Span Element
The <span> element is an inline container for text and can be used to group text for styling purposes. However, as <span> is a generic container to separate pieces of text from a larger body of text, its use should be avoided if a more semantic element is available.

<p><span>This text</span> may be styled differently than the surrounding text.</p>
<strong> Strong Element
The <strong> element highlights important, serious, or urgent text and browsers will normally render this highlighted text in bold by default.

<p>This is <strong>important</strong> text!</p>
# HTML Element
An HTML element is a piece of content in an HTML document and uses the following syntax: opening tag + content + closing tag. In the code provided:

<p> is the opening tag.
Hello World! is the content.
</p> is the closing tag.
<p>Hello World!</p>
# HTML Tag
The syntax for a single HTML tag is an opening angle bracket < followed by the element name and a closing angle bracket >. Here is an example of an opening <div> tag.

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
