# Web Development Learning

Welcome to my web development learning repository.

## Topics
- HTML
- CSS
- JavaScript
- Projects

## Goal
To become a full-stack web developer by building projects and learning new technologies.# Web-development
"My web development learning journey with HTML, CSS, JavaScript, and projects."
Web development is the process of creating and maintaining websites and web applications that run on the internet.
Main Parts:
Frontend Development
The part users see and interact with.
Technologies: HTML, CSS, JavaScript.
Backend Development
Handles server-side logic, databases, and user authentication.
Languages: Python, Java, PHP, Node.js, etc.
Database
Stores website data such as user accounts, products, and orders.
Examples: MySQL, PostgreSQL, MongoDB.
How a Website Works:
A user enters a website URL in a browser.
The browser sends a request to the server.
The server processes the request, retrieves data if needed, and sends a response.
The browser displays the webpage.
Uses of Web Development:
Business websites
E-commerce sites (Amazon, Flipkart)
Social media platforms (Instagram, Facebook)
Online learning websites
Banking and government portals
Skills to Learn:
HTML
CSS
JavaScript
Git & GitHub
A frontend framework (React)
A backend technology (Node.js, Django, or Spring Boot)
SQL or Moable
HTML (HyperText Markup Language)
Definition: HTML is the standard markup language used to create the structure of web pages.
Uses of HTML
Creates headings and paragraphs
Adds images and videos
Creates links
Builds tables and forms
Organizes webpage content
Basic HTML Structure<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first HTML page.</p>
</body>
</html>Common HTML Tags
<html> – Root element
<head> – Contains page information
<title> – Page title
<body> – Visible content
<h1> to <h6> – Headings
<p> – Paragraph
<a> – Link
<img> – Image
<div> – Container
<ul> / <ol> – Lists
<table> – Table
<form> – FormHTML Document Structure
Every HTML page follows a basic structure.
HTML
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is my first web page.</p>
</body>
</html>
Explanation of Each Tag
1. <!DOCTYPE html>
Declares that the document is an HTML5 document.
Helps the browser display the page correctly.
2. <html>
The root element of the HTML document.
All other HTML elements are placed inside it.
3. <head>
Contains information about the webpage.
This information is not displayed on the page.
4. <title>
Sets the title shown on the browser tab.
Example:
HTML
<title>My Website</title>
5. <body>
Contains all the content visible to users.
Such as headings, paragraphs, images, links, tables, and forms.
Example:
HTML
<body>
    <h1>Hello!</h1>
    <p>Welcome to my website.</p>
</body>HTML Elements and HTML Tags
What is an HTML Element?
An HTML element consists of a start tag, content, and an end tag.
Example:
HTML
<p>This is a paragraph.</p>
<p> → Start tag
This is a paragraph. → Content
</p> → End tag
What is an HTML Tag?
An HTML tag is a keyword enclosed in angle brackets (< >) that tells the browser how to display content.
Examples:
<h1> – Heading
<p> – Paragraph
<a> – Link
<img> – Image
<br> – Line break
Common HTML Tags
Tag
Purpose
<h1> to <h6>
Headings
<p>
Paragraph
<a>
Hyperlink
<img>
Image
<br>
Line break
<hr>
Horizontal line
<ul>
Unordered list
<ol>
Ordered list
<li>
List item
<table>
Table
<form>
Form
Example
HTML
<!DOCTYPE html>
<html>
<body>
    <h1>My Website</h1>
    <p>Welcome to HTML.</p>
    <a href="https://github.com">Visit GitHub</a>
</body>
    </html>
HTML Elements and HTML Tags
What is an HTML Element?
An HTML element consists of a start tag, content, and an end tag.
Example:
HTML
<p>This is a paragraph.</p>
<p> → Start tag
This is a paragraph. → Content
</p> → End tag
What is an HTML Tag?
An HTML tag is a keyword enclosed in angle brackets (< >) that tells the browser how to display content.
Examples:
<h1> – Heading
<p> – Paragraph
<a> – Link
<img> – Image
<br> – Line break
Common HTML Tags
Tag
Purpose
<h1> to <h6>
Headings
<p>
Paragraph
<a>
Hyperlink
<img>
Image
<br>
Line break
<hr>
Horizontal line
<ul>
Unordered list
<ol>
Ordered list
<li>
List item
<table>
Table
<form>
Form
Example
HTML
<!DOCTYPE html>
<html>
<body>
    <h1>My Website</h1>
    <p>Welcome to HTML.</p>
    <a href="https://github.com">Visit GitHub</a>
</body>
</html>HTML Attributes
What are HTML Attributes?
HTML attributes provide additional information about HTML elements. They are written inside the opening tag.
Syntax
HTML
<tagname attribute="value">Content</tagname>
Common HTML Attributes
1. href
Used to specify the destination URL of a link.
HTML
<a href="https://github.com">Visit GitHub</a>
2. src
Used to specify the path of an image.
HTML
<img src="image.jpg">
3. alt
Displays alternative text if the image cannot be loaded.
HTML
<img src="image.jpg" alt="Nature Image">
4. id
Gives a unique identifier to an HTML element.
HTML
<p id="intro">Welcome!</p>
5. class
Groups elements so they can share the same CSS styles.
HTML
<p class="text">Hello World</p>
6. style
Adds CSS styles directly to an element.
HTML
<h1 style="color: blue;">Welcome</h1>
Example
HTML
<!DOCTYPE html>
<html>
<body>

<a href="https://github.com">GitHub</a>

<img src="logo.png" alt="Logo">

<h1 style="color:red;">Hello</h1>

</body>
</html>
HTML Headings
Definition
HTML headings are used to define titles and headings on a webpage. HTML provides six heading levels, from <h1> to <h6>.
<h1> – Largest and most important heading
<h2> – Second-level heading
<h3> – Third-level heading
<h4> – Fourth-level heading
<h5> – Fifth-level heading
<h6> – Smallest and least important heading
Syntax
HTML
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Section Heading</h3>
<h4>Sub Section</h4>
<h5>Small Heading</h5>
<h6>Smallest Heading</h6>
Example
HTML
<!DOCTYPE html>
<html>
<body>

<h1>Welcome to My Website</h1>
<h2>About Us</h2>
<h3>Our Services</h3>
<h4>Contact Information</h4>
<h5>Support</h5>
<h6>Thank You</h6>

</body>HTML Paragraphs, Line Break, and Horizontal Rule
1. HTML Paragraph (<p>)
Definition
The <p> tag is used to create a paragraph of text on a webpage.
Syntax
HTML
<p>This is a paragraph.</p>
Example
HTML
<p>Welcome to HTML. HTML is used to create web pages.</p>
2. HTML Line Break (<br>)
Definition
The <br> tag is used to break a line and move the next text to a new line.
Syntax
HTML
Line 1<br>
Line 2
Example
HTML
<p>Hello!<br>Welcome to my website.</p>
Output:
Hello!
Welcome to my website.
3. HTML Horizontal Rule (<hr>)
Definition
The <hr> tag inserts a horizontal line to separate sections of a webpage.
Syntax
HTML
<hr>
Example
HTML
<h1>About Us</h1>
<hr>
<p>We provide web development training.</p>
</html>
HTML headings are used to define the titles and headings of a webpage. HTML provides six heading tags, from <h1> (largest) to <h6> (smallest).
HTML Lists
Definition
HTML lists are used to display a group of related items in an organized way.
There are three types of lists in HTML:
1. Ordered List (<ol>)
An ordered list displays items with numbers.
Example:
HTML
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
Output:
HTML
CSS
JavaScript
2. Unordered List (<ul>)
An unordered list displays items with bullet points.
Example:
HTML
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Mango</li>
</ul>
Output:
Apple
Banana
Mango
3. List Item (<li>)
The <li> tag is used to define each item in an ordered or unordered list.
Example:
HTML
<li>HTML</li>HTML lists are used to organize and display related items. HTML provides three main list tags:
<ol> – Ordered (numbered) list
<ul> – Unordered (bulleted) list
<li> – List itemHTML Tables
Definition
An HTML table is used to display data in rows and columns.
Main Table Tags
<table> – Creates a table.
<tr> – Creates a table row.
<th> – Creates a table header.
<td> – Creates a table data (cell).
Syntax
HTML
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Gyan</td>
    <td>20</td>
  </tr>
</table>
Example
HTML
<!DOCTYPE html>
<html>
<body>

<h2>Student Details</h2>

<table border="1">
  <tr>
    <th>Name</th>
    <th>Roll No</th>
    <th>Branch</th>
  </tr>
  <tr>
    <td>divyapriya</td>
    <td>101</td>
    <td>CSE</td>
  </tr>
  <tr>
    <td>Rahul</td>
    <td>102</td>
    <td>CSE</td>
  </tr>
</table>

</body>
</html>
Output
Name
Roll No
Branch
divyapriya
101
CSE
Rahul
102
CSEHTML tables are used to display data in rows and columns. The main tags used are:
<table> – Creates the table
<tr> – Creates a row
<th> – Creates a header cell
<td> – Creates a data cell
HTML Forms
Definition
An HTML form is used to collect user input, such as a name, email, password, or phone number, and send it to a server for processing.
Common Form Tags
<form> – Creates a form.
<label> – Defines a label for an input field.
<input> – Creates an input field.
<textarea> – Creates a multi-line text box.
<select> – Creates a drop-down list.
<option> – Defines an item in the drop-down list.
<button> – Creates a button.
Example
HTML
<!DOCTYPE html>
<html>
<body>

<h2>Student Registration Form</h2>

<form>
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br><br>

  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email"><br><br>

  <label for="password">Password:</label><br>
  <input type="password" id="password" name="password"><br><br>

  <button type="submit">Submit</button>
</form>

</body>
</html>
Common Input Types
text – Single-line text
password – Password field
email – Email address
number – Numeric input
date – Date picker
radio – Radio button
checkbox – Checkbox
file – File upload
submit – Submit button

HTML Semantic Elements
Definition
HTML semantic elements are tags that clearly describe the meaning and purpose of the content they contain. They make web pages easier to understand for browsers, search engines, and developers.
Common Semantic Elements
1. <header>
Represents the header of a webpage or section.
HTML
<header>
  <h1>My Website</h1>
</header>
2. <nav>
Contains navigation links.
HTML
<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
3. <section>
Defines a section of related content.
HTML
<section>
  <h2>About Us</h2>
  <p>We provide web development training.</p>
</section>
4. <article>
Represents independent content such as a blog post or news article.
HTML
<article>
  <h2>Latest News</h2>
  <p>HTML is easy to learn.</p>
</article>
5. <aside>
Contains related information, such as a sidebar.
HTML
<aside>
  <p>Related Links</p>
</aside>
6. <footer>
Represents the footer of a webpage.
HTML
<footer>
  <p>&copy; 2026 My Website</p>
</footer>
    HTML semantic elements are tags that describe the meaning and purpose of the content they contain. Examples include <header>, <nav>, <section>, <article>, <aside>, and <footer
HTML forms are used to collect user information and send it to a server. The main form tags are <form>, <input>, <label>, <textarea>, <select>, <option>, and <button>.
HTML5 Features
Definition
HTML5 is the latest version of HTML. It introduces new elements, multimedia support, graphics, and APIs that make web development easier and more powerful.
Features of HTML5
1. Audio (<audio>)
Used to play audio files on a web page.
HTML
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>
2. Video (<video>)
Used to play video files.
HTML
<video width="320" controls>
  <source src="movie.mp4" type="video/mp4">
</video>
3. Canvas (<canvas>)
Used to draw graphics, charts, and animations with JavaScript.
HTML
<canvas id="myCanvas" width="200" height="100"></canvas>
4. SVG (<svg>)
Used to create scalable vector graphics.
HTML
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" />
</svg>
5. Local Storage
Stores data in the browser even after it is closed.
Example:
localStorage.setItem("name", "Gyan");
6. Geolocation API
Gets the user's current location (with permission).
navigator.geolocation.getCurrentPosition(showPosition);
Advantages of HTML5
Supports audio and video without extra plugins.
Improves performance.
Supports modern web applications.
Works well on mobile devices.
Includes new semantic elements.HTML5 is the latest version of HTML that provides new semantic elements, multimedia support, graphics, browser storage, and APIs to build modern, interactive websites.CSS (Cascading Style Sheets) – Introduction
What is CSS?
CSS (Cascading Style Sheets) is a stylesheet language used to style and design HTML web pages. It controls the appearance of elements such as colors, fonts, spacing, layouts, and animations.
Why is CSS Used?
Adds colors to web pages.
Changes font styles and sizes.
Controls spacing and alignment.
Creates attractive layouts.
Makes websites responsive for different screen sizes.
Features of CSS
Easy to learn
Reduces code repetition
Separates content (HTML) from design (CSS)
Improves website appearance
Supports responsive web design
Basic CSS Syntax
selector {
  property: value;
}
Example
h1 {
  color: blue;
  font-size: 30px;
}
In this example:
h1 → Selector
color and font-size → Properties
blue and 30px → Values
Complete Example
HTML
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
}

p {
  color: green;
  font-size: 18px;
}
</style>
</head>
<body>

<h1>Welcome to CSS</h1>
<p>This paragraph is styled using CSS.</p>

</body>
</html>CSS (Cascading Style Sheets) is a stylesheet language used to control the appearance, layout, and design of HTML web pages.
Next Topic
Types of CSS
Inline CSS
Internal CSS
External CSS
Types of CSS
There are three types of CSS used to style HTML pages.
1. Inline CSS
Definition
Inline CSS is written directly inside an HTML element using the style attribute.
Example
HTML
<h1 style="color: blue;">Welcome to CSS</h1>
Advantages
Easy for small changes.
Styles only one element.
Disadvantages
Not suitable for large websites.
Difficult to maintain.
2. Internal CSS
Definition
Internal CSS is written inside the <style> tag in the <head> section of an HTML document.
Example
HTML
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
      color: blue;
    }
  </style>
</head>
<body>
  <h1>Welcome to CSS</h1>
</body>
</html>
Advantages
Styles a single webpage.
Easy to manage for small projects.
3. External CSS
Definition
External CSS is written in a separate .css file and linked to an HTML page.
HTML File
HTML
<head>
  <link rel="stylesheet" href="style.css">
</head>
CSS File (style.css)
h1 {
  color: blue;
}
Advantages
Reusable across multiple webpages.
Easy to maintain.
Best for large websites.
Difference Between the Three Types
Type
Location
Best Use
Inline CSS
Inside the HTML element
Small changes
Internal CSS
Inside the <style> tag
Single webpage
External CSS
Separate .css file
Multiple webpagesInterview/Exam Answer
CSS can be applied in three ways:
Inline CSS – Uses the style attribute inside an HTML element.
Internal CSS – Uses the <style> tag inside the <head> section.
External CSS – Uses a separate .css file linked with the <link> tag.
CSS Selectors (Element Selector, Class Selector, ID Selector, Universal Selector, and Group Selector).
CSS Selectors
Definition
CSS selectors are used to select HTML elements so that styles can be applied to them.
Types of CSS Selectors
1. Element Selector
Selects all elements of a particular tag.
Example:
p {
  color: blue;
}
This applies the color blue to all <p> elements.
2. ID Selector (#)
Selects a single element with a specific id.
HTML:
HTML
<h1 id="title">Welcome</h1>
CSS:
#title {
  color: red;
}
3. Class Selector (.)
Selects all elements with the same class.
HTML:
HTML
<p class="text">Hello</p>
<p class="text">Welcome</p>
CSS:
.text {
  color: green;
}
4. Universal Selector (*)
Selects all elements on the page.
* {
  margin: 0;
  padding: 0;
}
5. Group Selector (,)
Applies the same style to multiple elements.
h1, p {
  color: purple;
}CSS selectors are patterns used to select HTML elements and apply styles to them.
Common selectors are:
Element Selector (p)
ID Selector (#id)
Class Selector (.class)
Universal Selector (*)
Group Selector (,)
CSS Selectors
Definition
CSS selectors are used to select HTML elements so that styles can be applied to them.
Types of CSS Selectors
1. Element Selector
Selects all elements of a particular tag.
Example:
p {
  color: blue;
}
This applies the color blue to all <p> elements.
2. ID Selector (#)
Selects a single element with a specific id.
HTML:
HTML
<h1 id="title">Welcome</h1>
CSS:
#title {
  color: red;
}
3. Class Selector (.)
Selects all elements with the same class.
HTML:
HTML
<p class="text">Hello</p>
<p class="text">Welcome</p>
CSS:
.text {
  color: green;
}
4. Universal Selector (*)
Selects all elements on the page.
* {
  margin: 0;
  padding: 0;
}
5. Group Selector (,)
Applies the same style to multiple elements.
h1, p {
  color: purple;
}Common selectors are:
Element Selector (p)
ID Selector (#id)
Class Selector (.class)
Universal Selector (*)
Group Selector (,)
CSS Colors, Backgrounds, and Borders
1. CSS Colors
Definition
The color property is used to change the text color of an HTML element.
Example
h1 {
  color: blue;
}
You can use:
Color names: red, blue, green
Hex values: #FF0000
RGB values: rgb(255, 0, 0)
2. CSS Backgrounds
Definition
The background-color property is used to set the background color of an element.
Example
body {
  background-color: lightblue;
}
Background Image
body {
  background-image: url("background.jpg");
}
3. CSS Borders
Definition
The border property is used to add a border around an HTML element.
Example
p {
  border: 2px solid black;
}
This means:
2px → Border thickness
solid → Border style
black → Border color
Complete Example
HTML
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightyellow;
}

h1 {
  color: blue;
}

p {
  border: 2px solid black;
}
</style>
</head>
<body>

<h1>Welcome to CSS</h1>
<p>This is a paragraph with a border.</p>

</body>
</html>
CSS Colors are used to change the text color of elements.
CSS Backgrounds are used to set background colors or images.
CSS Borders are used to add borders around HTML elements.
CSS Box Model
Definition
The CSS Box Model describes how every HTML element is displayed as a rectangular box. It consists of Content, Padding, Border, and Margin.
Parts of the Box Model
1. Content
The actual text, image, or other content inside the element.
2. Padding
The space between the content and the border.
padding: 20px;
3. Border
The line that surrounds the padding and content.
border: 2px solid black;
4. Margin
The space outside the border, separating the element from other elements.
margin: 20px;
Diagram
+---------------------------+
|         Margin            |
|  +---------------------+  |
|  |      Border         |  |
|  |  +---------------+  |  |
|  |  |   Padding     |  |  |
|  |  | +-----------+ |  |  |
|  |  | | Content   | |  |  |
|  |  | +-----------+ |  |  |
|  |  +---------------+  |  |
|  +---------------------+  |
+---------------------------+
Example
HTML
<!DOCTYPE html>
<html>
<head>
<style>
div {
  width: 200px;
  padding: 20px;
  border: 2px solid blue;
  margin: 30px;
}
</style>
</head>
<body>

<div>
  Welcome to CSS Box Model
</div>

</body>
</html>
The CSS Box Model is a layout model that represents every HTML element as a box consisting of:
Content – The actual data.
Padding – Space between the content and the border.
Border – Surrounds the content and padding.
Margin – Space outside the border.
CSS Text Properties
Definition
CSS text properties are used to control the appearance of text, such as its color, size, font, alignment, spacing, and decoration.
Common CSS Text Properties
1. color
Changes the text color.
p {
  color: blue;
}
2. font-size
Changes the size of the text.
p {
  font-size: 20px;
}
3. font-family
Changes the font style.
p {
  font-family: Arial, sans-serif;
}
4. font-weight
Makes the text bold or lighter.
p {
  font-weight: bold;
}
5. text-align
Aligns the text.
h1 {
  text-align: center;
}
Values:
left
center
right
justify
6. text-decoration
Adds or removes text decorations.
a {
  text-decoration: none;
}
Common values:
underline
overline
line-through
none
7. text-transform
Changes the case of the text.
h1 {
  text-transform: uppercase;
}
Values:
uppercase
lowercase
capitalize
8. line-height
Sets the space between lines.
p {
  line-height: 1.8;
}
Complete Example
HTML
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  text-align: center;
  text-transform: uppercase;
}

p {
  font-size: 18px;
  font-family: Arial, sans-serif;
  line-height: 1.8;
}
</style>
</head>
<body>

<h1>Welcome to CSS</h1>
<p>This is an example of CSS text properties.</p>
CSS text properties are used to control the appearance of text. Common properties include:
color
font-size
font-family
font-weight
text-align
text-decoration
text-transform
line-height
Next Topic
CSS Positioning (static, relative, absolute, fixed, and sticky) – an important topic for web development.
CSS Positioning
Definition
CSS positioning is used to control where an HTML element appears on a webpage.
There are five types of positioning:
1. static
Default position of all HTML elements.
The element follows the normal page flow.
div {
  position: static;
}
2. relative
The element is positioned relative to its normal position.
You can move it using top, bottom, left, or right.
div {
  position: relative;
  left: 20px;
}
3. absolute
The element is positioned relative to its nearest positioned parent.
It is removed from the normal page flow.
div {
  position: absolute;
  top: 50px;
  left: 100px;
}
4. fixed
The element stays in the same position even when the page is scrolled.
div {
  position: fixed;
  bottom: 10px;
  right: 10px;
}
5. sticky
The element behaves like relative until a scroll position is reached, then it sticks in place.
div {
  position: sticky;
  top: 0;
}
Difference Between Position Types
Position
Description
static
Default position
relative
Moves relative to its original position
absolute
Positioned relative to the nearest positioned parent
fixed
Stays fixed on the screen while scrolling
sticky
Sticks to a position after scrolling
CSS positioning controls the location of HTML elements on a webpage. The five position values are:
static
relative
absolute
fixed
sticky
CSS Flexbox
Definition
CSS Flexbox (Flexible Box Layout) is a layout model used to arrange, align, and distribute elements efficiently inside a container.
It helps create responsive layouts with less code.
Important Flexbox Properties
1. display: flex
Makes an element a flex container.
.container {
  display: flex;
}
2. flex-direction
Sets the direction of flex items.
.container {
  flex-direction: row;
}
Values:
row (default)
column
row-reverse
column-reverse
3. justify-content
Aligns items horizontally.
.container {
  justify-content: center;
}
Common values:
flex-start
center
flex-end
space-between
space-around
space-evenly
4. align-items
Aligns items vertically.
.container {
  align-items: center;
}
Common values:
stretch
flex-start
center
flex-end
5. gap
Adds space between flex items.
.container {
  gap: 20px;
}
Example
HTML
<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}

.box {
  width: 100px;
  height: 100px;
  background-color: lightblue;
}
</style>
</head>
<body>

<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
</div>

</body>
</html>
Advantages
Creates responsive layouts easily.
Aligns items horizontally and vertically.
Reduces the need for complex CSS.
Makes layout design simpler.
CSS Flexbox is a one-dimensional layout model used to arrange, align, and distribute elements inside a container efficiently. The main properties are display: flex, flex-direction, justify-content, align-items, and gap.
CSS Grid Layout
Definition
CSS Grid Layout is a two-dimensional layout system used to arrange elements in rows and columns. It is ideal for creating complex and responsive webpage layouts.
Important Grid Properties
1. display: grid
Makes an element a grid container.
.container {
  display: grid;
}
2. grid-template-columns
Defines the number and width of columns.
.container {
  grid-template-columns: 200px 200px 200px;
}
Or using equal-width columns:
.container {
  grid-template-columns: repeat(3, 1fr);
}
3. grid-template-rows
Defines the height of rows.
.container {
  grid-template-rows: 100px 100px;
}
4. gap
Adds space between rows and columns.
.container {
  gap: 20px;
}
<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}

.box {
  background-color: lightblue;
  padding: 20px;
  text-align: center;
}
</style>
</head>
<body>

<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
  <div class="box">4</div>
  <div class="box">5</div>
  <div class="box">6</div>
</div>

</body>
</html>
Example
HTML
Advantages
Creates layouts with rows and columns.
Makes responsive web design easier.
Organizes webpage content efficiently.
Reduces complex CSS code.
Difference Between Flexbox and Grid
Flexbox
Grid
One-dimensional (row or column)
Two-dimensional (rows and columns)
Best for aligning items
Best for complete page layouts
CSS Grid Layout is a two-dimensional layout system that arranges elements into rows and columns. It is widely used for building responsive and structured webpage layouts.
Responsive Web Design (RWD)
Definition
Responsive Web Design (RWD) is a web design approach that makes a website automatically adjust its layout and content to fit different screen sizes such as mobiles, tablets, laptops, and desktops.
Why is RWD Important?
Improves user experience.
Makes websites mobile-friendly.
Works on all screen sizes.
Reduces the need for separate mobile websites.
1. Viewport
The viewport tells the browser how to display the webpage on different devices.
Example
HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
2. Media Queries
Media queries apply different CSS styles based on the screen size.
Example
@media screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
In this example, the background becomes light blue when the screen width is 600px or less.
3. Responsive Images
Images can be made responsive by setting their width to 100%.
img {
  max-width: 100%;
  height: auto;
}
Complete Example
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  font-family: Arial;
}

@media screen and (max-width: 600px) {
  body {
    background-color: lightgray;
  }
}
</style>
</head>
<body>

<h1>Responsive Web Design</h1>
<p>Resize the browser window to see the effect.</p>

</body>
</html>
HTML
Advantages
Mobile-friendly websites.
Better user experience.
Improved SEO.
One website works on all devices.
Easier maintenance.
Responsive Web Design (RWD) is a technique used to create websites that automatically adapt to different screen sizes using viewport settings, flexible layouts, and CSS media queries.
Bootstrap – Introduction
Definition
Bootstrap is a free and open-source CSS framework used to create responsive, mobile-friendly, and attractive websites quickly. It provides pre-designed CSS classes and JavaScript components.
Why Use Bootstrap?
Develops websites faster.
Mobile-first framework.
Responsive design.
Easy to use.
Consistent look across browsers.
Features of Bootstrap
Responsive Grid System
Predefined CSS classes
Buttons
Forms
Navigation bars (Navbar)
Cards
Alerts
Modals
Carousel
Icons (Bootstrap Icons)
How to Use Bootstrap
Add the Bootstrap CSS link inside the <head> section of your HTML page.
HTML
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
Example
HTML
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="container">
  <h1 class="text-primary">Welcome to Bootstrap</h1>
  <button class="btn btn-success">Click Me</button>
</div>

</body>
</html>
Common Bootstrap Classes
Class
Purpose
container
Creates a responsive container
row
Creates a row
col
Creates a column
btn
Styles a button
btn-primary
Blue button
btn-success
Green button
text-primary
Blue text
text-center
Centers text
Advantages
Easy to learn
Saves development time
Responsive by default
Large collection of ready-made components
Works well on different devices
Bootstrap is a free, open-source CSS framework used to build responsive and mobile-friendly websites quickly using prebuilt CSS classes and UI components.
JavaScript – Introduction
What is JavaScript?
JavaScript (JS) is a programming language used to make web pages interactive and dynamic. It works together with HTML and CSS.
HTML → Structure of the webpage
CSS → Style and design
JavaScript → Functionality and interactivity
Why Use JavaScript?
Respond to button clicks
Validate forms
Create animations
Display alerts and pop-up messages
Update webpage content without reloading
Build interactive web applications
Features of JavaScript
Easy to learn
Runs in all modern web browsers
Object-oriented
Event-driven
Lightweight and fast
Simple Example
HTML
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Example</h2>

<button onclick="showMessage()">Click Me</button>

<script>
function showMessage() {
  alert("Welcome to JavaScript!");
}
</script>

</body>
</html>
When the button is clicked, a message box appears with: "Welcome to JavaScript!"
Applications of JavaScript
Interactive websites
Games
Web applications
Online forms
Real-time chat applications
JavaScript is a scripting/programming language used to make web pages interactive and dynamic. It adds functionality such as form validation, animations, event handling, and dynamic content updates.
JavaScript Variables
Definition
A variable is a named container used to store data such as numbers, text, or Boolean values.
In JavaScript, variables are declared using:
var
let
const
1. var
Used to declare a variable.
Can be redeclared and updated.
Example
var name = "divyapriya";
console.log(name);
2. let
Used to declare a block-scoped variable.
Can be updated, but cannot be redeclared in the same scope.
Example
let age = 20;
age = 21;
console.log(age);
3. const
Used to declare a constant variable.
Cannot be updated or redeclared.
Example
const country = "India";
console.log(country);
Difference Between var, let, and const
var
let
const
Can be redeclared
Cannot be redeclared in the same scope
Cannot be redeclared
Can be updated
Can be updated
Cannot be updated
Function-scoped
Block-scoped
Block-scoped
variable is used to store data in JavaScript.
var: Can be redeclared and updated.
let: Can be updated but cannot be redeclared in the same scope.
const: Cannot be updated or redeclared after it is assigned.
JavaScript Data Types
Definition
Data types define the type of data that a variable can store in JavaScript.
Types of Data Types
1. Number
Stores numeric values.
let age = 20;
Example: 10, 25, 3.14
2. String
Stores text enclosed in single or double quotes.
let name = "divyapriya";
Example: "Hello", "JavaScript"
3. Boolean
Stores only two values: true or false.
let isStudent = true;
4. Undefined
A variable that has been declared but not assigned a value.
let x;
console.log(x);
Output:
undefined
5. Null
Represents an intentionally empty value.
let data = null;
6. Object
Stores data as key-value pairs.
let student = {
  name: "divyapriya",
  age: 18
};
7. Array
Stores multiple values in a single variable.
let fruits = ["Apple", "Banana", "Mango"];
Summary Table
Data Type
Example
Number
100, 3.14
String
"Hello"
Boolean
true, false
Undefined
let x;
Null
null
Object
{name: "Gyan"}
Array
["Apple", "Banana"]
JavaScript data types specify the kind of data stored in a variable. The main data types are:
Number
String
Boolean
Undefined
Null
Object
Array
JavaScript Operators
Definition
Operators are special symbols used to perform operations on variables and values.
Types of JavaScript Operators
1. Arithmetic Operators
Used to perform mathematical calculations.
Operator
Meaning
Example
+
Addition
10 + 5 = 15
-
Subtraction
10 - 5 = 5
*
Multiplication
10 * 5 = 50
/
Division
10 / 5 = 2
%
Modulus (Remainder)
10 % 3 = 1
Example:
let a = 10;
let b = 5;
console.log(a + b);
2. Assignment Operators
Used to assign values to variables.
Operator
Example
=
x = 10
+=
x += 5
-=
x -= 5
*=
x *= 2
/=
x /= 2
3. Comparison Operators
Used to compare two values.
Operator
Meaning
==
Equal to
===
Strictly equal
!=
Not equal
>
Greater than
<
Less than
>=
Greater than or equal to
<=
Less than or equal to
Example:
console.log(10 > 5);
4. Logical Operators
Used to combine conditions.
Operator
Meaning
&&
AND
`

!
NOT
Example:
console.log(true && false);
5. Increment and Decrement Operators
++ → Increases a value by 1.
-- → Decreases a value by 1.
Example:
let x = 5;
x++;
console.log(x);
Output:
6
JavaScript operators are symbols used to perform operations on variables and values. The main types are:
Arithmetic Operators
Assignment Operators
Comparison Operators
Logical Operators
Increment/Decrement Operators
JavaScript Conditional Statements
Definition
Conditional statements are used to make decisions in a JavaScript program. They execute different blocks of code based on whether a condition is true or false.
1. if Statement
Executes a block of code only if the condition is true.
Syntax
if (condition) {
  // code
}
Example
let age = 20;

if (age >= 18) {
  console.log("Eligible to vote");
}
2. if...else Statement
Executes one block if the condition is true, otherwise executes another block.
Example
let age = 16;

if (age >= 18) {
  console.log("Eligible to vote");
} else {
  console.log("Not eligible to vote");
}
3. else if Statement
Checks multiple conditions.
Example
let marks = 85;

if (marks >= 90) {
  console.log("Grade A+");
} else if (marks >= 75) {
  console.log("Grade A");
} else {
  console.log("Grade B");
}
4. switch Statement
Used when there are many possible values for one variable.
Example
let day = 2;

switch (day) {
  case 1:
    console.log("Monday");
    break;
  case 2:
    console.log("Tuesday");
    break;
  default:
    console.log("Invalid Day");
}
Conditional statements are used to make decisions in JavaScript based on conditions. The main conditional statements are:
if
if...else
else if
switch
JavaScript Loops
Definition
Loops are used to execute a block of code repeatedly until a specified condition becomes false.
Types of Loops
1. for Loop
Used when you know how many times the loop should run.
Syntax
for (initialization; condition; increment) {
  // code
}
Example
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
Output:
1
2
3
4
5
2. while Loop
Executes the code as long as the condition is true.
Syntax
while (condition) {
  // code
}
Example
let i = 1;

while (i <= 5) {
  console.log(i);
  i++;
}
3. do...while Loop
Executes the code at least once, then checks the condition.
Syntax
do {
  // code
} while (condition);
Example
let i = 1;

do {
  console.log(i);
  i++;
} while (i <= 5);
4. break Statement
Terminates (stops) the loop immediately.
Example
for (let i = 1; i <= 5; i++) {
  if (i === 3) {
    break;
  }
  console.log(i);
}
Output:
1
2
5. continue Statement
Skips the current iteration and continues with the next one.
Example
for (let i = 1; i <= 5; i++) {
  if (i === 3) {
    continue;
  }
  console.log(i);
}
Output:
1
2
4
5
JavaScript loops are used to execute a block of code repeatedly. The main loops are:
for
while
do...while
The break statement exits a loop, while the continue statement skips the current iteration and proceeds to the next one.
JavaScript Functions
Definition
A function is a reusable block of code that performs a specific task. Functions help reduce code duplication and make programs easier to maintain.
1. Function Declaration
Syntax
function functionName() {
  // code
}
Example
function greet() {
  console.log("Welcome to JavaScript");
}

greet();
Output:
Welcome to JavaScript
2. Function with Parameters
Parameters allow you to pass values to a function.
Example
function add(a, b) {
  console.log(a + b);
}

add(10, 20);
Output:
30
3. Function with Return Value
The return statement sends a value back from the function.
Example
function multiply(a, b) {
  return a * b;
}

let result = multiply(5, 4);
console.log(result);
Output:
20
4. Function Expression
A function can also be stored in a variable.
Example
const greet = function() {
  console.log("Hello!");
};

greet();
5. Arrow Function
Arrow functions provide a shorter syntax for writing functions.
Example
const greet = () => {
  console.log("Hello!");
};

greet();
Advantages of Functions
Reusable code
Reduces code duplication
Easier to test and maintain
Improves readability
A function is a reusable block of code that performs a specific task. Functions can accept parameters, return values using the return statement, and can be written as function declarations, function expressions, or arrow functions.
JavaScript Arrays
Definition
A JavaScript array is a special variable used to store multiple values in a single variable.
1. Creating an Array
Syntax
let arrayName = [value1, value2, value3];
Example
let fruits = ["Apple", "Banana", "Mango"];
2. Accessing Array Elements
Array indexing starts from 0.
Example
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits[0]);
console.log(fruits[1]);
Output:
Apple
Banana
3. Changing an Array Element
let fruits = ["Apple", "Banana", "Mango"];
fruits[1] = "Orange";

console.log(fruits);
4. Common Array Methods
push()
Adds an element to the end of the array.
let fruits = ["Apple", "Banana"];
fruits.push("Mango");
pop()
Removes the last element.
fruits.pop();
shift()
Removes the first element.
fruits.shift();
unshift()
Adds an element to the beginning.
fruits.unshift("Grapes");
length
Returns the number of elements.
console.log(fruits.length);
5. Loop Through an Array
Using for Loop
let fruits = ["Apple", "Banana", "Mango"];

for (let i = 0; i < fruits.length; i++) {
  console.log(fruits[i]);
}
Using forEach()
fruits.forEach(function(item) {
  console.log(item);
});
6. map() Method
Creates a new array by applying a function to each element.
let numbers = [1, 2, 3];

let doubled = numbers.map(num => num * 2);

console.log(doubled);
Output:
[2, 4, 6]
7. filter() Method
Creates a new array with elements that satisfy a condition.
let numbers = [10, 20, 30, 40];

let result = numbers.filter(num => num > 20);

console.log(result);
Output:
[30, 40]
A JavaScript array is used to store multiple values in a single variable. Common array methods include:
push()
pop()
shift()
unshift()
length
forEach()
map()
filter()
JavaScript Objects
Definition
A JavaScript object is a collection of key-value pairs used to store related data and functions together.
1. Creating an Object
Syntax
let objectName = {
  key1: value1,
  key2: value2
};
Example
let student = {
  name: "divyapriya",
  age: 18,
  branch: "CSE"
};
2. Accessing Object Properties
Using Dot Notation
console.log(student.name);
Using Bracket Notation
console.log(student["age"]);
Output:
divyapriya
18
4. Adding a New Property
student.college = "ABC College";
5. Updating a Property
student.age = 21;
6. Deleting a Property
delete student.branch;
7. Object Methods
Objects can contain functions called methods.
let student = {
  name: "divyapriya",
  greet: function() {
    console.log("Hello!");
  }
};

student.greet();
Output:
Hello!
7. Looping Through an Object
Using for...in
let student = {
  name: "Gyan",
  age: 20
};

for (let key in student) {
  console.log(key + ": " + student[key]);
}
8. Object.keys() and Object.values()
console.log(Object.keys(student));
console.log(Object.values(student));
Output:
["name", "age"]
["Gyan", 20]
JavaScript object is a collection of key-value pairs used to store related data and behavior. Properties are accessed using dot notation (object.property) or bracket notation (object["property"]). Objects can also contain methods (functions).
JavaScript DOM (Document Object Model)
Definition
The Document Object Model (DOM) is a programming interface for HTML documents. It represents a web page as a tree of objects, allowing JavaScript to access, modify, add, or remove HTML elements dynamically.
Why is DOM Used?
Change text and HTML content
Change CSS styles
Handle user events (click, input, etc.)
Add or remove HTML elements
Create interactive web pages
1. Selecting Elements
By ID
document.getElementById("title");
By Class Name
document.getElementsByClassName("text");
By Tag Name
document.getElementsByTagName("p");
Using querySelector()
document.querySelector("#title");
Using querySelectorAll()
document.querySelectorAll("p");
2. Changing HTML Content
document.getElementById("title").innerHTML = "Welcome to JavaScript";
3. Changing CSS Styles
document.getElementById("title").style.color = "blue";
4. Handling Events
Example
HTML
<button onclick="showMessage()">Click Me</button>

<script>
function showMessage() {
  alert("Button Clicked!");
}
</script>
5. Complete Example
HTML
<!DOCTYPE html>
<html>
<body>

<h1 id="title">Hello</h1>
<button onclick="changeText()">Click Me</button>

<script>
function changeText() {
  document.getElementById("title").innerHTML = "Welcome!";
}
</script>

</body>
</html>
The DOM (Document Object Model) is a tree-like representation of an HTML document that allows JavaScript to access and modify webpage content, structure, and styles dynamically.
JavaScript Events
Definition
JavaScript events are actions that occur in the browser, such as clicking a button, typing on the keyboard, moving the mouse, or submitting a form. JavaScript can respond to these events by executing code.
Common JavaScript Events
1. onclick
Occurs when a user clicks an element.
HTML
<button onclick="showMessage()">Click Me</button>

<script>
function showMessage() {
  alert("Button Clicked!");
}
</script>
2. ondblclick
Occurs when a user double-clicks an element.
HTML
<button ondblclick="alert('Double Clicked!')">
  Double Click
</button>
3. onmouseover
Occurs when the mouse pointer moves over an element.
HTML
<p onmouseover="this.style.color='red'">
  Move the mouse over me.
</p>
4. onmouseout
Occurs when the mouse pointer leaves an element.
HTML
<p onmouseout="this.style.color='black'">
  Move the mouse away.
</p>
5. onkeydown
Occurs when a keyboard key is pressed.
HTML
<input type="text" onkeydown="alert('Key Pressed')">
6. onkeyup
Occurs when a keyboard key is released.
HTML
<input type="text" onkeyup="console.log('Key Released')">
7. onchange
Occurs when the value of an input field changes.
HTML
<select onchange="alert('Option Changed')">
  <option>HTML</option>
  <option>CSS</option>
</select>
8. onsubmit
Occurs when a form is submitted.
HTML
<form onsubmit="alert('Form Submitted')">
  <input type="submit" value="Submit">
</form>
JavaScript events are actions performed by the user or browser that trigger JavaScript code. Common events include:
onclick
ondblclick
onmouseover
onmouseout
onkeydown
onkeyup
onchange
onsubmit
JavaScript ES6 Features
Definition
ES6 (ECMAScript 2015) is a major update to JavaScript that introduced many new features, making code simpler, cleaner, and easier to write.
1. let
Declares a block-scoped variable.
let age = 20;
console.log(age);
2. const
Declares a constant variable.
const country = "India";
console.log(country);
3. Template Literals
Used to create strings with embedded variables using backticks (`).
let name = "Gyan";
console.log(`Welcome ${name}`);
Output:
Welcome Gyan
4. Destructuring
Extracts values from arrays or properties from objects.
Array Example
let colors = ["Red", "Green", "Blue"];
let [a, b] = colors;

console.log(a);
console.log(b);
5. Spread Operator (...)
Copies or combines arrays and objects.
let arr1 = [1, 2];
let arr2 = [...arr1, 3, 4];

console.log(arr2);
Output:
[1, 2, 3, 4]
6. Rest Operator (...)
Collects multiple values into a single array.
function sum(...numbers) {
  console.log(numbers);
}

sum(10, 20, 30);
7. Default Parameters
Assigns default values to function parameters.
function greet(name = "Guest") {
  console.log(name);
}

greet();
Output:
Guest
8. Promises
Promises handle asynchronous operations.
let promise = new Promise((resolve) => {
  resolve("Success");
});

promise.then(result => console.log(result));
9. Async/Await
Makes asynchronous code easier to read and write.
async function greet() {
  return "Hello";
}

greet().then(console.log);
ES6 is the 2015 version of JavaScript that introduced modern features such as:
let
const
Template literals
Destructuring
Spread operator
Rest operator
Default parameters
Promises
async/await
These features make JavaScript code more readable, efficient, and easier to maintain.
After JavaScript Events, the next important topic is JavaScript Event Listeners.
JavaScript Event Listeners
Definition
An event listener is a method that waits for an event (such as a click, key press, or mouse movement) and executes a function when that event occurs.
The most commonly used method is addEventListener().
Syntax
element.addEventListener("event", function);
1. Click Event
HTML
<button id="btn">Click Me</button>

<script>
document.getElementById("btn").addEventListener("click", function() {
    alert("Button Clicked!");
});
</script>
2. Mouse Over Event
document.getElementById("btn").addEventListener("mouseover", function() {
    console.log("Mouse is over the button");
});
3. Key Press Event
document.addEventListener("keydown", function() {
    console.log("Key Pressed");
});
4. Input Event
HTML
<input type="text" id="name">

<script>
document.getElementById("name").addEventListener("input", function() {
    console.log("Typing...");
});
</script>
Advantages of addEventListener()
Can attach multiple events to the same element.
Keeps JavaScript separate from HTML.
Makes code easier to read and maintain.
JavaScript Form Validation
Definition
Form validation is the process of checking whether the user has entered valid data before the form is submitted.
Why is Form Validation Used?
Prevents empty fields.
Ensures correct email format.
Checks password length.
Reduces invalid data.
Improves security and user experience.
Example 1: Check Empty Input
<!DOCTYPE html>
<html>
<body>

<form onsubmit="return validateForm()">
  Name: <input type="text" id="name">
  <input type="submit" value="Submit">
</form>

<script>
function validateForm() {
  let name = document.getElementById("name").value;

  if (name === "") {
    alert("Name cannot be empty");
    return false;
  }

  return true;
}
</script>

</body>
</html>
HTML
Example 2: Email Validation
let email = document.getElementById("email").value;

if (!email.includes("@")) {
  alert("Enter a valid email address");
}
Example 3: Password Validation
let password = document.getElementById("password").value;

if (password.length < 8) {
  alert("Password must be at least 8 characters");
}
Common Validation Checks
Name should not be empty.
Email should contain @.
Password should have at least 8 characters.
Phone number should contain only digits.
Required fields must be filled.
JavaScript BOM (Browser Object Model)
Definition
The Browser Object Model (BOM) allows JavaScript to interact with the browser window. It provides objects and methods to control browser features such as alerts, navigation, screen information, and browser history.
Main BOM Objects
1. window
The window object is the top-level object in the browser. All global JavaScript objects, functions, and variables belong to it.
Example
window.alert("Welcome!");
or simply
alert("Welcome!");
2. location
The location object contains information about the current webpage URL.
Example
console.log(location.href);
Reload the page:
location.reload();
3. history
The history object allows navigation through the browser history.
Example
history.back();
Go to the next page:
history.forward();
4. navigator
The navigator object provides information about the browser.
Example
console.log(navigator.userAgent);
5. screen
The screen object provides information about the user's screen.
Example
console.log(screen.width);
console.log(screen.height);
Common BOM Methods
`alert
JavaScript Browser Object Model (BOM)
Definition
The Browser Object Model (BOM) allows JavaScript to interact with the web browser. It provides objects to control the browser window, access browser information, and perform browser-related operations.
Main BOM Objects
1. window
The window object is the top-level object in the browser. All global JavaScript objects, functions, and variables belong to it.
Example
alert("Welcome!");
or
window.alert("Welcome!");
2. location
The location object contains information about the current webpage URL.
Example
console.log(window.location.href);
To reload the page:
location.reload();
3. history
The history object allows navigation through the browser history.
Example
history.back();
Go to the next page:
history.forward();
4. navigator
The navigator object provides information about the browser.
Example
console.log(navigator.userAgent);
5. screen
The screen object provides information about the user's screen.
Example
console.log(screen.width);
console.log(screen.height);
Common BOM Methods
alert()
Displays a message box.
alert("Hello!");
confirm()
Displays a confirmation dialog.
confirm("Are you sure?");
prompt()
Displays an input dialog.
let name = prompt("Enter your name:");
The Browser Object Model (BOM) is a collection of browser-related objects that allow JavaScript to interact with the browser. Important BOM objects are:
window
location
history
navigator
screen
Common methods include:
alert()
confirm()
prompt()
