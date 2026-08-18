# Web Development Learning

Welcome to my web devolopment learning repository.

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
  name: "divyapriya"
  age: 18
};

for (let key in student) {
  console.log(key + ": " + student[key]);
}
8. Object.keys() and Object.values()
console.log(Object.keys(student));
console.log(Object.values(student));
Output:
["name", "age"]
["divyapriya", 18]
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
let age = 18;
console.log(age);
2. const
Declares a constant variable.
const country = "India";
console.log(country);
3. Template Literals
Used to create strings with embedded variables using backticks (`).
let name = "divyapriya";
console.log(`Welcome ${name}`);
Output:
Welcome divyapriya
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
JSON (JavaScript Object Notation)
Definition
JSON (JavaScript Object Notation) is a lightweight data-interchange format used to store and exchange data between a client and a server. It is easy for humans to read and write and easy for machines to parse.
Features of JSON
Lightweight and simple
Human-readable
Language-independent
Used for data exchange in web applications
Supports objects and arrays
JSON Syntax
JSON stores data as key-value pairs.
{
  "name": "divyapriya",
  "age": 18,
  "branch": "CSE"
}
Rules:
Keys must be enclosed in double quotes.
Data is written as key : value.
Objects are enclosed in { }.
Arrays are enclosed in [ ].
JSON Data Types
JSON supports:
String
Number
Boolean
Object
Array
Null
JSON.parse()
Converts a JSON string into a JavaScript object.
Example
let jsonData = '{"name":"divyapriya","age":18}';

let obj = JSON.parse(jsonData);

console.log(obj.name);
Output:
Gyan
JSON.stringify()
Converts a JavaScript object into a JSON string.
Example
let student = {
  name: "divyapriya",
  age: 18
};

let jsonString = JSON.stringify(student);

console.log(jsonString);
Output:
{"name":"divyapriya","age":18}
Uses of JSON
Sending data between client and server
Web APIs
Storing configuration data
Exchanging information between applications
JSON (JavaScript Object Notation) is a lightweight format used to store and exchange data. It represents data as key-value pairs. JSON.parse() converts a JSON string into a JavaScript object, and JSON.stringify() converts a JavaScript object into a JSON string.
AJAX (Asynchronous JavaScript and XML)
Definition
AJAX (Asynchronous JavaScript and XML) is a technique that allows a web page to send and receive data from a server without reloading the entire page.
Although AJAX originally used XML, today it commonly uses JSON.
Why Use AJAX?
Updates data without refreshing the page.
Makes websites faster and more interactive.
Improves user experience.
Reduces server load.
How AJAX Works
User performs an action (clicks a button, submits a form, etc.).
JavaScript sends a request to the server.
The server processes the request.
The server sends back data (usually JSON).
JavaScript updates the webpage without reloading it.
AJAX Using XMLHttpRequest
let xhr = new XMLHttpRequest();

xhr.open("GET", "data.json", true);

xhr.onload = function() {
    console.log(xhr.responseText);
};

xhr.send();
AJAX Using fetch() (Modern Method)
fetch("data.json")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.log(error));
Advantages of AJAX
No full page reload.
Faster response time.
Better user experience.
Saves bandwidth.
Used in modern web applications.
Applications of AJAX
Gmail
Google Maps
Facebook
Online shopping websites
Live search suggestions
AJAX (Asynchronous JavaScript and XML) is a web development technique that enables JavaScript to communicate with a server asynchronously, allowing parts of a webpage to update without reloading the entire page. Modern AJAX applications commonly use the fetch() API and JSON.
JavaScript Fetch API
Definition
The Fetch API is a modern JavaScript feature used to send HTTP requests (such as GET, POST, PUT, and DELETE) and receive data from a server. It is promise-based and is commonly used in modern web applications.
1. GET Request
A GET request is used to retrieve data from a server.
Example
fetch("https://api.example.com/users")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.log(error));
2. POST Request
A POST request is used to send data to a server.
Example
fetch("https://api.example.com/users", {
  method: "POST",
  headers: {
    "Content-Type": "application/json"
  },
  body: JSON.stringify({
    name: "divyapriya",
    age: 18
  })
})
.then(response => response.json())
.then(data => console.log(data))
.catch(error => console.log(error));
3. Using async and await
async and await make asynchronous code easier to read.
Example
async function getUsers() {
  try {
    const response = await fetch("https://api.example.com/users");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.log(error);
  }
}

getUsers();
Advantages of Fetch API
Easy to use
Promise-based
Supports async/await
Handles network requests efficiently
Used in modern web applications
The Fetch API is a modern JavaScript interface used to make HTTP requests to a server. It supports methods like GET, POST, PUT, and DELETE, and works with Promises and async/await for asynchronous programming.
JavaScript Local Storage and Session Storage
Definition
Local Storage and Session Storage are browser storage mechanisms used to store data on the user's browser.
Local Storage stores data permanently (until it is deleted).
Session Storage stores data only for the current browser tab/session. The data is removed when the tab or browser is closed.
1. Local Storage
Store Data
localStorage.setItem("name", "Gyan");
Get Data
let name = localStorage.getItem("name");
console.log(name);
Remove Data
localStorage.removeItem("name");
Clear All Data
localStorage.clear();
2. Session Storage
Store Data
sessionStorage.setItem("user", "Gyan");
Get Data
let user = sessionStorage.getItem("user");
console.log(user);
Remove Data
sessionStorage.removeItem("user");
Clear All Data
sessionStorage.clear();
Difference Between Local Storage and Session Storage
Local Storage
Session Storage
Data remains until manually deleted
Data is deleted when the browser/tab is closed
Shared across browser tabs of the same origin
Available only in the current tab
Suitable for long-term storage
Suitable for temporary storage
Advantages
Easy to store user preferences.
No server request is needed.
Improves website performance.
Simple key-value storage.
Local Storage stores data permanently in the browser until it is removed manually, while Session Storage stores data only for the current browser session and deletes it when the tab or browser is closed.
Local Storage in JavaScript
Definition
Local Storage is a browser storage mechanism used to store data in the user's browser. The data remains available even after the browser is closed, until it is manually removed.
Main Methods
1. setItem() – Store Data
localStorage.setItem("name", "Gyan");
2. getItem() – Retrieve Data
let name = localStorage.getItem("name");
console.log(name);
Output:
Gyan
3. removeItem() – Remove One Item
localStorage.removeItem("name");
4. clear() – Remove All Items
localStorage.clear();
Simple Example
HTML
<!DOCTYPE html>
<html>
<body>

<h2>Local Storage Example</h2>

<script>
localStorage.setItem("name", "Gyan");

let name = localStorage.getItem("name");

document.write("Name: " + name);
</script>

</body>
</html>
Output
Name: Gyan
Local Storage is a web storage mechanism that allows websites to store data in the browser as key-value pairs. The main methods are setItem(), getItem(), removeItem(), and clear().
Session Storage in JavaScript
Definition
Session Storage is a browser storage mechanism used to store data temporarily. The data is available only during the current browser tab/session and is generally removed when that tab is closed.
Main Methods
1. setItem() – Store Data
sessionStorage.setItem("name", "Gyan");
2. getItem() – Retrieve Data
let name = sessionStorage.getItem("name");
console.log(name);
Output:
Gyan
3. removeItem() – Remove One Item
sessionStorage.removeItem("name");
4. clear() – Remove All Data
sessionStorage.clear();
Simple Example
HTML
<!DOCTYPE html>
<html>
<body>

<h2>Session Storage Example</h2>

<script>
sessionStorage.setItem("name", "Gyan");

let name = sessionStorage.getItem("name");

document.write("Name: " + name);
</script>

</body>
</html>
Output
Name: Gyan
Local Storage vs Session Storage
Local Storage
Session Storage
Data remains until manually deleted
Data is temporary
Data generally remains after browser restart
Data generally ends when the tab/session is closed
Can be used for long-term browser data
Used for temporary session data
Session Storage is used to store data temporarily in the browser. It provides methods such as setItem(), getItem(), removeItem(), and clear().
JavaScript Error Handling
Definition
Error handling is the process of detecting and handling errors in a JavaScript program so that the program can respond properly instead of stopping unexpectedly.
Main Keywords
1. try
Contains the code that may produce an error.
2. catch
Handles the error if one occurs.
3. finally
Executes whether an error occurs or not.
4. throw
Used to create a custom error.
Example
try {
  let result = 10 / 0;
  console.log(result);
} catch (error) {
  console.log("An error occurred");
} finally {
  console.log("Program completed");
}
Example with throw
let age = 15;

try {
  if (age < 18) {
    throw new Error("Age must be 18 or above");
  }
} catch (error) {
  console.log(error.message);
}
Output:
Age must be 18 or above
Advantages
Prevents unexpected program termination.
Helps identify errors.
Improves application reliability.
Makes debugging easier.
JavaScript error handling is used to detect and handle errors in a program. The main keywords are try, catch, finally, and throw.
JavaScript Promises
Definition
A Promise is an object in JavaScript that represents the eventual result of an asynchronous operation. It can either succeed or fail.
For example, fetching data from a server may take some time. A Promise helps handle the result when the operation finishes.
Promise States
A Promise has three states:
Pending – The operation is still in progress.
Fulfilled – The operation completed successfully.
Rejected – The operation failed.
Creating a Promise
let promise = new Promise((resolve, reject) => {
  let success = true;

  if (success) {
    resolve("Operation successful");
  } else {
    reject("Operation failed");
  }
});
Using .then() and .catch()
.then() → Handles a successful result.
.catch() → Handles an error.
promise
  .then(result => {
    console.log(result);
  })
  .catch(error => {
    console.log(error);
  });
Output:
Operation successful
Using async and await
Promises are commonly used with async and await.
async function getData() {
  try {
    let result = await promise;
    console.log(result);
  } catch (error) {
    console.log(error);
  }
}

getData();
Advantages of Promises
Handles asynchronous operations.
Makes code easier to manage.
Helps avoid deeply nested callbacks.
Works with .then(), .catch(), and async/await.
Promise is a JavaScript object that represents the result of an asynchronous operation. It has three states: Pending, Fulfilled, and Rejected. Promises can be handled using .then(), .catch(), and async/await.
JavaScript Async/Await
Definition
Async/Await is a modern JavaScript feature used to handle asynchronous operations in a simpler and more readable way. It works with Promises.
1. async
The async keyword is used before a function. An async function always returns a Promise.
Example
async function greet() {
  return "Hello World";
}

greet().then(result => {
  console.log(result);
});
Output:
Hello World
2. await
The await keyword pauses the execution of an async function until the Promise is completed.
Example
async function getData() {
  let result = await Promise.resolve("Data received");
  console.log(result);
}

getData();
Output:
Data received
3. Async/Await with try...catch
try...catch is used to handle errors.
async function getData() {
  try {
    let result = await Promise.resolve("Success");
    console.log(result);
  } catch (error) {
    console.log(error);
  }
}

getData();
4. Async/Await with Fetch API
A common use is getting data from a server.
async function getUsers() {
  try {
    const response = await fetch("https://api.example.com/users");
    const data = await response.json();

    console.log(data);
  } catch (error) {
    console.log("Error:", error);
  }
}

getUsers();
Advantages
Easy to read and understand.
Makes asynchronous code look like normal sequential code.
Works with Promises.
Error handling is easy using try...catch.
Async/Await is a modern JavaScript feature used to handle asynchronous operations. The async keyword defines an asynchronous function, while await waits for a Promise to complete. It makes asynchronous code easier to read and maintain.
JavaScript Modules
Definition
JavaScript Modules allow us to divide a large JavaScript program into separate, reusable files. This makes code easier to organize, maintain, and reuse.
There are two main keywords:
export
import
1. Export
The export keyword is used to make a variable, function, or class available to another JavaScript file.
math.js
export function add(a, b) {
  return a + b;
}
2. Import
The import keyword is used to use exported code from another file.
main.js
import { add } from "./math.js";

console.log(add(10, 20));
Output:
30
3. Using Modules in HTML
Use type="module" in the <script> tag.
HTML
<script type="module" src="main.js"></script>
4. Default Export
A module can have one default export.
message.js
export default function greet() {
  console.log("Hello!");
}
main.js
import greet from "./message.js";

greet();
Advantages of JavaScript Modules
Organizes code into separate files.
Makes code reusable.
Easier to maintain large projects.
Reduces code duplication.
Helps manage complex applications.
JavaScript Modules are used to divide code into separate files and reuse it when needed. The export keyword makes code available to other modules, and the import keyword brings that code into another module
JavaScript Object-Oriented Programming (OOP)
Definition
Object-Oriented Programming (OOP) is a programming approach that organizes code using objects and classes.
JavaScript supports important OOP concepts such as:
Class
Object
Constructor
Encapsulation
Inheritance
Polymorphism
1. Class
A class is a blueprint or template for creating objects.
class Student {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}
2. Object
An object is an instance of a class.
let student1 = new Student("Gyan", 20);

console.log(student1.name);
Output:
Gyan
3. Constructor
A constructor is a special method that automatically runs when an object is created.
class Student {
  constructor(name) {
    this.name = name;
  }
}
4. Method
A method is a function defined inside a class.
class Student {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log("Hello " + this.name);
  }
}

let student = new Student("Gyan");
student.greet();
Output:
Hello divaypriya
5. Inheritance
Inheritance allows one class to acquire properties and methods from another class.
class Student {
  study() {
    console.log("Student is studying");
  }
}

class CollegeStudent extends Student {
  code() {
    console.log("Student is coding");
  }
}

let s = new CollegeStudent();

s.study();
s.code();
6. Encapsulation
Encapsulation means keeping data and the methods that operate on it together inside a class and controlling access to internal data.
7. Polymorphism
Polymorphism means the same method name can behave differently in different classes.
OOP in JavaScript is a programming approach based on objects and classes. The major concepts are classes, objects, constructors, encapsulation, inheritance, and polymorphism.
JavaScript Classes in Detail
1. What is a Class?
A class is a blueprint or template used to create objects.
Syntax
class ClassName {
  constructor() {
    // properties
  }

  method() {
    // code
  }
}
2. Constructor
The constructor() method is automatically called when a new object is created.
class Student {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}
Here:
name and age are properties.
this refers to the current object.
3. Creating an Object
Use the new keyword to create an object.
let student1 = new Student("Gyan", 20);

console.log(student1.name);
console.log(student1.age);
Output:
divyapriya
18
4. Methods in a Class
A method is a function defined inside a class.
class Student {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log("Hello " + this.name);
  }
}

let student = new Student("divyapriya");

student.greet();
Output:
Hello divyapriya
5. Inheritance with extends
The extends keyword allows one class to inherit from another class.
class Student {
  study() {
    console.log("Student is studying");
  }
}

class CollegeStudent extends Student {
  code() {
    console.log("Student is coding");
  }
}
Now CollegeStudent can use the study() method from Student.
let student = new CollegeStudent();

student.study();
student.code();
6. super() Keyword
The super() keyword is used to call the constructor of the parent class.
class Student {
  constructor(name) {
    this.name = name;
  }
}

class CollegeStudent extends Student {
  constructor(name, branch) {
    super(name);
    this.branch = branch;
  }
}

let student = new CollegeStudent("divyapriya", "CSE");

console.log(student.name);
console.log(student.branch);
Output:
divyapriya
CSE
A JavaScript class is a blueprint for creating objects. The constructor() initializes object properties, methods define object behavior, extends is used for inheritance, and super() calls the parent class constructor
JavaScript OOP Concepts in Detail
JavaScript OOP mainly has 4 important concepts:
Encapsulation
Inheritance
Polymorphism
Abstraction
1. Encapsulation
Encapsulation means keeping data and methods together inside a class and controlling access to the data.
Example:
class Student {
  #marks = 90;

  getMarks() {
    return this.#marks;
  }
}

let student = new Student();

console.log(student.getMarks());
Output:
90
Here, #marks is a private property.
2. Inheritance
Inheritance allows a child class to use properties and methods of a parent class.
Example:
class Animal {
  eat() {
    console.log("Animal is eating");
  }
}

class Dog extends Animal {
  bark() {
    console.log("Dog is barking");
  }
}

let dog = new Dog();

dog.eat();
dog.bark();
Output:
Animal is eating
Dog is barking
Here, Dog inherits the eat() method from Animal.
3. Polymorphism
Polymorphism means "many forms." The same method can have different implementations in different classes.
Example:
class Animal {
  sound() {
    console.log("Animal makes a sound");
  }
}

class Dog extends Animal {
  sound() {
    console.log("Dog barks");
  }
}

class Cat extends Animal {
  sound() {
    console.log("Cat meows");
  }
}

let dog = new Dog();
let cat = new Cat();

dog.sound();
cat.sound();
Output:
Dog barks
Cat meows
4. Abstraction
Abstraction means showing only the necessary information and hiding unnecessary implementation details.
For example, when you use a car, you use the steering wheel and pedals without needing to know every internal detail of how the engine works.
In JavaScript, abstraction can be achieved using classes, methods, and controlled access to data.
Quick Summary
Concept
Meaning
Encapsulation
Protect and control data
Inheritance
Reuse properties and methods
Polymorphism
Same method, different behavior
Abstraction
Hide unnecessary implementation details
The four major OOP concepts are Encapsulation, Inheritance, Polymorphism, and Abstraction. They help developers create reusable, organized, and maintainable code.
JavaScript Prototype and Prototypal Inheritance
1. What is a Prototype?
In JavaScript, every object can have a prototype. A prototype is another object from which an object can inherit properties and methods.
This is called prototypal inheritance.
2. Simple Example
let student = {
  name: "divyapriya"
};

console.log(student.toString());
Here, toString() is not directly defined inside student. JavaScript can access it through the object's prototype chain.
3. Prototype with Constructor Function
function Student(name) {
  this.name = name;
}

Student.prototype.greet = function() {
  console.log("Hello " + this.name);
};

let student1 = new Student("Gyan");

student1.greet();
Output
Hello divyapriya
The greet() method is stored on Student.prototype and can be used by objects created using Student.
4. Prototype Chain
When JavaScript looks for a property or method:
It first checks the object itself.
If it doesn't find it, it checks the object's prototype.
It continues searching up the prototype chain.
If nothing is found, it returns undefined or produces an error depending on the operation.
5. Class and Prototypes
JavaScript class syntax internally uses prototypes.
class Student {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log("Hello " + this.name);
  }
}
The greet() method is available through the class's prototype.
A prototype is an object from which other JavaScript objects can inherit properties and methods. Prototypal inheritance allows objects to reuse functionality through the prototype chain. JavaScript classes also use prototypes internally.
JavaScript this Keyword
Definition
The this keyword refers to the object that is associated with the current execution context. Its value depends on how a function is called.
1. this Inside an Object
When a regular method is called through an object, this refers to that object.
let student = {
  name: "divyapriya",

  greet: function() {
    console.log("Hello " + this.name);
  }
};

student.greet();
Output:
Hello divyapriya
Here, this.name refers to student.name.
2. this Inside a Class
In a class method, this refers to the current object.
class Student {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log("Hello " + this.name);
  }
}

let student = new Student("divyapriya");
student.greet();
Output:
Hello divyapriya
3. this in Arrow Functions
Arrow functions do not have their own this. They use this from their surrounding scope.
let student = {
  name: "divyapriya",

  greet: () => {
    console.log(this.name);
  }
};
For object methods, a regular function is generally preferred when you want this to refer to the object.
4. this with call()
The call() method can explicitly set the value of this.
function greet() {
  console.log("Hello " + this.name);
}

let student = {
  name: "divyapriya"
};

greet.call(student);
Output:
Hello divyapriya
Simple Summary
Situation
Meaning of this
Object method
The object that called the method
Class method
The current object
Arrow function
Inherits this from surrounding scope
call()
Can explicitly set this
The this keyword in JavaScript refers to the object associated with the current execution context. Its value depends on how a function is called. In object methods and class methods, this commonly refers to the current object.
JavaScript Closures
Definition
A closure is a function that remembers and can access variables from its outer (surrounding) function, even after the outer function has finished executing.
Simple Example
function outer() {
  let message = "Hello";

  function inner() {
    console.log(message);
  }

  return inner;
}

let result = outer();

result();
Output
Hello
Here, the inner() function remembers the message variable from the outer() function. This is called a closure.
Another Example
function counter() {
  let count = 0;

  return function() {
    count++;
    console.log(count);
  };
}

let myCounter = counter();

myCounter();
myCounter();
myCounter();
Output
1
2
3
The inner function remembers the count variable. Each time it is called, the value is updated.
Uses of Closures
Data privacy
Maintaining state
Creating function factories
Callbacks
Event handlers
A closure is created when an inner function remembers and accesses variables from its outer function's scope, even after the outer function has completed execution.
JavaScript Higher-Order Functions
Definition
A Higher-Order Function (HOF) is a function that does at least one of these:
Takes another function as an argument.
Returns another function as a result.
1. Function as an Argument
function greet(name) {
  console.log("Hello " + name);
}

function processUser(callback) {
  callback("Gyan");
}

processUser(greet);
Output
Hello Gyan
Here, greet is passed as an argument to processUser().
2. map()
map() is a Higher-Order Function. It applies a function to every element of an array.
let numbers = [1, 2, 3];

let result = numbers.map(function(num) {
  return num * 2;
});

console.log(result);
Output
[2, 4, 6]
3. filter()
filter() creates a new array containing elements that satisfy a condition.
let numbers = [10, 20, 30, 40];

let result = numbers.filter(function(num) {
  return num > 20;
});

console.log(result);
Output
[30, 40]
4. reduce()
reduce() processes all elements and returns a single value.
let numbers = [1, 2, 3, 4];

let sum = numbers.reduce(function(total, num) {
  return total + num;
}, 0);

console.log(sum);
Output
10
Common Higher-Order Functions
map()
filter()
reduce()
forEach()
find()
some()
every()
A Higher-Order Function is a function that accepts another function as an argument or returns a function as a result. Common examples include map(), filter(), and reduce().
JavaScript Callback Functions
Definition
A callback function is a function that is passed as an argument to another function and is executed later.
Simple Example
function greet(name) {
  console.log("Hello " + name);
}

function processUser(callback) {
  callback("divyapriya");
}

processUser(greet);
Output
Hello divyapriya
Here, greet is passed to processUser() as a callback function.
Callback with setTimeout()
Callbacks are commonly used for asynchronous operations.
setTimeout(function() {
  console.log("Hello after 2 seconds");
}, 2000);
The function runs after approximately 2 seconds.
Callback with Array Methods
Using forEach()
let fruits = ["Apple", "Banana", "Mango"];

fruits.forEach(function(fruit) {
  console.log(fruit);
});
Output
Apple
Banana
Mango
The function passed to forEach() is a callback function.
Callback vs Higher-Order Function
Callback Function
Higher-Order Function
A function passed to another function
A function that accepts or returns another function
Example: function passed to forEach()
Example: forEach(), map(), filter()
A callback function is a function passed as an argument to another function and executed when required. Callbacks are commonly used in event handling, asynchronous programming, setTimeout(), and array methods.
JavaScript Callback Hell
Definition
Callback Hell happens when multiple callbacks are nested inside each other, making the code difficult to read, understand, and maintain.
It is also called the Pyramid of Doom.
Example
doTask1(function() {
  doTask2(function() {
    doTask3(function() {
      doTask4(function() {
        console.log("All tasks completed");
      });
    });
  });
});
As the number of nested callbacks increases, the code becomes harder to manage.
Problems with Callback Hell
Code becomes difficult to read.
Difficult to debug.
Difficult to maintain.
Error handling becomes complicated.
Code structure becomes deeply nested.
Solution: Promises
Promises provide a cleaner way to handle asynchronous operations.
doTask1()
  .then(() => doTask2())
  .then(() => doTask3())
  .then(() => doTask4())
  .then(() => console.log("All tasks completed"))
  .catch(error => console.log(error));
Another Solution: Async/Await
async/await makes asynchronous code easier to read.
async function runTasks() {
  try {
    await doTask1();
    await doTask2();
    await doTask3();
    await doTask4();

    console.log("All tasks completed");
  } catch (error) {
    console.log(error);
  }
}
Callback Hell is a situation where multiple asynchronous callbacks are nested inside one another, making the code difficult to read and maintain. It can be avoided by using Promises and async/await.
JavaScript Event Loop
Definition
The Event Loop is a mechanism in JavaScript that allows it to handle asynchronous operations even though JavaScript is single-threaded.
It helps JavaScript manage tasks like:
setTimeout()
API requests
User events
Promises
Main Components
1. Call Stack
Executes JavaScript code one task at a time.
2. Web APIs
Browser features that handle asynchronous operations such as timers and network requests.
3. Callback Queue
Stores callback functions that are ready to be executed.
4. Microtask Queue
Stores Promise callbacks such as .then() and .catch().
5. Event Loop
Checks whether the Call Stack is empty and moves waiting tasks to it for execution.
Simple Example
console.log("Start");

setTimeout(function() {
  console.log("Timeout");
}, 0);

console.log("End");
Output
Start
End
Timeout
Why?
"Start" executes first.
setTimeout() is handled asynchronously.
"End" executes next.
After the Call Stack is empty, the callback runs.
"Timeout" is printed last.
Promise Example
console.log("Start");

Promise.resolve().then(function() {
  console.log("Promise");
});

console.log("End");
Output
Start
End
Promise
The Promise callback is placed in the Microtask Queue and runs after the synchronous code finishes.
The JavaScript Event Loop is responsible for handling asynchronous operations. It continuously checks the Call Stack and queues, allowing JavaScript to execute asynchronous callbacks when the Call Stack becomes empty.
JavaScript Regular Expressions (RegEx)
Definition
A Regular Expression (RegEx) is a pattern used to search, match, and validate text in JavaScript.
RegEx is commonly used for:
Email validation
Phone number validation
Password validation
Searching text
Replacing text
1. Creating a Regular Expression
Using / /
let pattern = /hello/;
This pattern searches for the word hello.
2. test() Method
The test() method checks whether a pattern exists in a string. It returns true or false.
let pattern = /hello/;

console.log(pattern.test("hello world"));
Output
true
3. match() Method
Used to find matching text.
let text = "I love JavaScript";

console.log(text.match(/JavaScript/));
4. replace() Method
Used to replace matching text.
let text = "Hello World";

let result = text.replace(/World/, "JavaScript");

console.log(result);
Output
Hello JavaScript
5. Common RegEx Symbols
Symbol
Meaning
^
Start of string
$
End of string
.
Any character
*
Zero or more times
+
One or more times
?
Zero or one time
[a-z]
Lowercase letters
[0-9]
Digits
Example: Check Only Numbers
let pattern = /^[0-9]+$/;

console.log(pattern.test("12345"));
Output
true
Example: Simple Email Validation
let email = "student@example.com";

let pattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

console.log(pattern.test(email));
Output
true
A Regular Expression (RegEx) is a sequence of characters that defines a search pattern. In JavaScript, RegEx is used for pattern matching, searching, replacing, and input validation.
JavaScript Map and Set
JavaScript provides Map and Set as built-in data structures for storing and managing data.
1. JavaScript Set
Definition
A Set is a collection of unique values. It does not allow duplicate values.
Creating a Set
let numbers = new Set([1, 2, 3, 3, 4]);

console.log(numbers);
The duplicate 3 is stored only once.
Common Set Methods
add()
Adds a new value.
numbers.add(5);
has()
Checks whether a value exists.
console.log(numbers.has(3));
Output:
true
delete()
Removes a value.
numbers.delete(3);
size
Returns the number of unique values.
console.log(numbers.size);
2. JavaScript Map
Definition
A Map stores data as key-value pairs.
Creating a Map
let student = new Map();

student.set("name", "divyapriya");
student.set("age", 18);
Common Map Methods
set()
Adds or updates a key-value pair.
student.set("branch", "CSE");
get()
Retrieves a value using its key.
console.log(student.get("name"));
Output:
divyapriya
has()
Checks whether a key exists.
console.log(student.has("age"));
delete()
Removes a key-value pair.
student.delete("age");
size
Returns the number of key-value pairs.
console.log(student.size);
Map vs Set
Map
Set
Stores key-value pairs
Stores only values
Keys are unique
Values are unique
Uses set() and get()
Uses add()
Example: name → divyapriya
Example: 1, 2, 3
A Set is a collection of unique values, while a Map is a collection of key-value pairs. Both are useful for efficiently storing and managing data in JavaScript.
JavaScript Memory Management and Garbage Collection
Definition
Memory Management is the process of allocating and freeing memory while a JavaScript program runs.
JavaScript automatically manages memory using a process called Garbage Collection.
1. Memory Allocation
When you create variables, objects, or arrays, JavaScript allocates memory for them.
Example
let name = "Gyan";

let student = {
  age: 20
};
Memory is allocated to store these values.
2. Garbage Collection
Garbage Collection automatically identifies and removes data that is no longer accessible or needed by the program.
Example
let student = {
  name: "Gyan"
};

student = null;
After assigning null, the original object may become unreachable. JavaScript's garbage collector can eventually free the memory used by that object.
3. Memory Leak
A memory leak occurs when a program unnecessarily keeps references to data that it no longer needs, causing memory usage to increase.
Common causes include:
Unused global variables
Unremoved event listeners
Timers that are not cleared
Unnecessary references to objects
4. setTimeout() and clearTimeout()
A timer can be cancelled using clearTimeout().
let timer = setTimeout(() => {
  console.log("Hello");
}, 5000);

clearTimeout(timer);
5. setInterval() and clearInterval()
An interval can be stopped using clearInterval().
let interval = setInterval(() => {
  console.log("Running");
}, 1000);

clearInterval(interval);
Memory management is the process of allocating and releasing memory during program execution. JavaScript automatically manages memory using Garbage Collection, which removes objects that are no longer reachable or needed.
JavaScript Web APIs
Definition
Web APIs are features provided by the browser that allow JavaScript to interact with the browser and perform tasks such as accessing webpage elements, making network requests, storing data, and using device features.
1. DOM API
Used to access and modify HTML elements.
document.getElementById("title").innerText = "Hello";
2. Fetch API
Used to communicate with servers and retrieve data.
fetch("https://example.com/data")
  .then(response => response.json())
  .then(data => console.log(data));
3. Web Storage API
Used to store data in the browser.
Local Storage
localStorage.setItem("name", "divyapriya");
Session Storage
sessionStorage.setItem("user", "divyapriya");
4. Timer API
Used to execute code after a specific time or repeatedly.
setTimeout()
setTimeout(() => {
  console.log("Hello");
}, 2000);
setInterval()
setInterval(() => {
  console.log("Running");
}, 1000);
5. Geolocation API
Used to request the user's geographical location, subject to permission.
navigator.geolocation.getCurrentPosition(position => {
  console.log(position.coords.latitude);
  console.log(position.coords.longitude);
});
6. Console API
Used mainly for debugging and displaying information.
console.log("Hello");
console.error("An error occurred");
Common Web APIs
Web API
Purpose
DOM API
Manipulate HTML
Fetch API
Communicate with servers
Web Storage API
Store browser data
Timer API
Handle timers
Geolocation API
Access location with permission
Console API
Debugging
Web APIs are browser-provided interfaces that allow JavaScript programs to interact with browser features and perform tasks such as DOM manipulation, network communication, data storage, timers, and geolocation.
JavaScript Web Workers
Definition
A Web Worker allows JavaScript code to run in a background thread, separate from the main webpage thread. It helps keep the user interface responsive during heavy computations.
Why Use Web Workers?
Performs heavy calculations in the background.
Prevents the webpage from becoming unresponsive.
Improves performance for CPU-intensive tasks.
1. Create a Worker File
Create a file called worker.js:
self.onmessage = function(event) {
  let result = event.data * 2;
  self.postMessage(result);
};
2. Create the Main JavaScript File
let worker = new Worker("worker.js");

worker.postMessage(10);

worker.onmessage = function(event) {
  console.log("Result:", event.data);
};
Output
Result: 20
How It Works
The main JavaScript creates a Web Worker.
postMessage() sends data to the worker.
The worker performs the task.
postMessage() sends the result back.
onmessage receives the result.
Important Methods
Method
Purpose
new Worker()
Creates a worker
postMessage()
Sends data
onmessage
Receives data
terminate()
Stops the worker
Stop a Worker
worker.terminate();
A Web Worker allows JavaScript to execute tasks in a background thread without blocking the main webpage. It is useful for heavy computations and helps keep the user interface responsive.
JavaScript Service Workers and Progressive Web Apps (PWA)
1. Service Worker
A Service Worker is a JavaScript file that runs in the background, separately from the webpage. It can help with caching, offline support, and handling network requests.
Basic Example
if ("serviceWorker" in navigator) {
  navigator.serviceWorker.register("sw.js")
    .then(() => {
      console.log("Service Worker Registered");
    })
    .catch(error => {
      console.log("Registration Failed", error);
    });
}
2. Progressive Web App (PWA)
A PWA is a web application that provides an app-like experience using modern web technologies.
Features of PWA
Works offline or with limited connectivity.
Can be installed on supported devices.
Can load quickly.
Can use caching for better performance.
Provides an app-like user experience.
3. Main Components of a PWA
Service Worker
Handles background tasks and caching.
Web App Manifest
Provides information about the app, such as its name and icons.
HTTPS
PWAs generally require a secure HTTPS connection for important features.
4. Simple Manifest Example
Create a file named manifest.json:
{
  "name": "My Web App",
  "short_name": "MyApp",
  "start_url": "/",
  "display": "standalone"
}
Link it in HTML:
HTML
<link rel="manifest" href="manifest.json">
Service Worker vs Web Worker
Service Worker
Web Worker
Used for caching and network-related tasks
Used for background computations
Can support offline functionality
Helps avoid blocking the main thread
Can work without an active webpage in some scenarios
Usually works while its associated page is active
Important for PWAs
Useful for CPU-intensive tasks
A Service Worker is a background JavaScript script that can handle tasks such as caching and network requests. A Progressive Web App (PWA) is a web application that provides an app-like experience and can offer features such as offline support and installation.
JavaScript Testing and Debugging
1. What is Testing?
Testing is the process of checking whether a JavaScript program works correctly and produces the expected output.
2. What is Debugging?
Debugging is the process of finding and fixing errors or bugs in a program.
3. Using console.log()
console.log() is commonly used to check values while debugging.
let a = 10;
let b = 20;

console.log(a + b);
Output:
30
4. Browser Developer Tools
You can open Developer Tools in Chrome or Edge by pressing:
F12 or Ctrl + Shift + I
Common tabs include:
Console – View errors and output.
Sources – View and debug JavaScript files.
Network – Monitor network requests.
Elements – Inspect and modify HTML and CSS.
5. Breakpoints
A breakpoint pauses program execution at a specific line so you can examine variables and program flow.
Example:
let x = 10;
let y = 20;

let result = x + y;

console.log(result);
You can set a breakpoint on the result line using the browser's Sources panel.
6. Unit Testing
Unit testing checks individual parts or functions of a program separately.
Example function:
function add(a, b) {
  return a + b;
}
Expected result:
add(2, 3) === 5
Popular JavaScript testing tools include:
Jest
Vitest
Mocha
7. Types of Testing
Type
Meaning
Unit Testing
Tests individual functions or components
Integration Testing
Tests how different parts work together
End-to-End Testing
Tests the complete application flow
JavaScript testing is used to verify that code works as expected, while debugging is the process of finding and fixing errors. Browser Developer Tools, console.log(), breakpoints, and testing frameworks such as Jest are commonly used.
JavaScript JSON
Definition
JSON (JavaScript Object Notation) is a lightweight format used to store and exchange data between applications, especially between a frontend and backend.
JSON is easy for both humans and computers to read.
1. JSON Example
{
  "name": "divyapriya",
  "age": 18,
  "branch": "CSE"
}
Here:
"name" is a key.
"divyapriya"  is its value.
Data is stored as key-value pairs.
3. JSON.stringify()
Converts a JavaScript object into a JSON string.
let student = {
  name: "divyapriya",
  age: 18
};

let jsonData = JSON.stringify(student);

console.log(jsonData);
Output
{"name":"divyapriya","age":18}
3. JSON.parse()
Converts a JSON string into a JavaScript object.
let jsonData = '{"name":"Gyan","age":20}';

let student = JSON.parse(jsonData);

console.log(student.name);
Output
Gyan
4. JSON with Fetch API
JSON is commonly used to receive data from a server.
fetch("https://example.com/data")
  .then(response => response.json())
  .then(data => {
    console.log(data);
  });
Here, response.json() converts the server response into a JavaScript object.
JSON Rules
Data is written using key-value pairs.
Keys must use double quotes.
Strings must use double quotes.
Objects use { }.
Arrays use [ ].
Functions are not valid JSON values.
JSON (JavaScript Object Notation) is a lightweight data format used to exchange data between a client and a server. In JavaScript, JSON.stringify() converts an object into a JSON string, while JSON.parse() converts a JSON string into an object.
JavaScript DOM (Document Object Model)
Definition
DOM stands for Document Object Model. It represents an HTML document as a tree of objects.
JavaScript uses the DOM to access, change, add, and remove HTML elements dynamically.
1. Selecting an Element by ID
HTML:
HTML
<h1 id="title">Hello</h1>
JavaScript:
let heading = document.getElementById("title");

console.log(heading);
2. Changing HTML Content
document.getElementById("title").innerText = "Welcome to JavaScript";
The text inside the <h1> changes.
3. Selecting Elements by Class
let items = document.getElementsByClassName("item");
4. Using querySelector()
Selects the first matching element.
let heading = document.querySelector("#title");
For a class:
let item = document.querySelector(".item");
5. Using querySelectorAll()
Selects all matching elements.
let items = document.querySelectorAll(".item");
6. Changing CSS
document.getElementById("title").style.fontSize = "30px";
7. Changing Attributes
document.getElementById("myImage").src = "image.jpg";
8. Creating a New Element
let paragraph = document.createElement("p");

paragraph.innerText = "This is a new paragraph.";

document.body.appendChild(paragraph);
9. Removing an Element
let element = document.getElementById("title");

element.remove();
Common DOM Methods
Method
Purpose
getElementById()
Select element by ID
getElementsByClassName()
Select elements by class
querySelector()
Select first matching element
querySelectorAll()
Select all matching elements
createElement()
Create a new element
appendChild()
Add an element
remove()
Remove an element
The DOM (Document Object Model) is a programming interface that represents an HTML document as a tree of objects. JavaScript uses the DOM to dynamically access, modify, create, and remove HTML elements.
JavaScript DOM Events
Definition
A DOM Event is an action or occurrence that happens in a webpage. JavaScript can detect these events and execute a function in response.
Common Events
click → User clicks an element
dblclick → User double-clicks
mouseover → Mouse moves over an element
mouseout → Mouse leaves an element
keydown → A keyboard key is pressed
keyup → A keyboard key is released
submit → A form is submitted
change → Input value changes
1. Using onclick
HTML
HTML
<button onclick="showMessage()">Click Me</button>
JavaScript
function showMessage() {
  alert("Button clicked!");
}
2. Using addEventListener()
addEventListener() is a commonly preferred way to attach event handlers.
HTML
HTML
<button id="btn">Click Me</button>
JavaScript
let button = document.getElementById("btn");

button.addEventListener("click", function() {
  alert("Button clicked!");
});
3. Keyboard Event
document.addEventListener("keydown", function(event) {
  console.log("Key pressed:", event.key);
});
When a key is pressed, its name is displayed in the console.
4. Form Submit Event
let form = document.getElementById("myForm");

form.addEventListener("submit", function(event) {
  event.preventDefault();
  console.log("Form submitted");
});
event.preventDefault() prevents the browser's default form submission behavior.
5. Event Object
The event object contains information about the event.
button.addEventListener("click", function(event) {
  console.log(event.type);
});
Output:
click
DOM Events are actions that occur on webpage elements, such as clicks, keyboard input, mouse movement, and form submission. JavaScript can respond to these events using event handlers such as onclick or the addEventListener() method.
JavaScript Event Bubbling and Event Capturing
When an event occurs on an HTML element, it travels through the DOM tree. This process is called Event Propagation.
There are two main phases:
Event Capturing
Event Bubbling
1. Event Bubbling
In Event Bubbling, the event starts from the target element and moves upward toward its parent elements.
Example
HTML
<div id="parent">
  <button id="child">Click Me</button>
</div>
document.getElementById("parent").addEventListener("click", function() {
  console.log("Parent clicked");
});

document.getElementById("child").addEventListener("click", function() {
  console.log("Button clicked");
});
When the button is clicked, the output is generally:
Button clicked
Parent clicked
The event moves from the button → parent.
2. Event Capturing
In Event Capturing, the event travels from the outer parent toward the target element.
To enable capturing, use true as the third argument.
document.getElementById("parent").addEventListener("click", function() {
  console.log("Parent clicked");
}, true);
The event travels from:
Parent → Child
3. stopPropagation()
The stopPropagation() method prevents the event from continuing to propagate through the DOM.
document.getElementById("child").addEventListener("click", function(event) {
  event.stopPropagation();
  console.log("Button clicked");
});
The parent event listener will not receive the event through propagation.
4. Event Delegation
Event Delegation is a technique where we attach one event listener to a parent element to handle events from its child elements.
Example
document.getElementById("parent").addEventListener("click", function(event) {
  if (event.target.id === "child") {
    console.log("Button clicked");
  }
});
This is useful when working with many child elements or dynamically added elements.
Difference
Event Bubbling
Event Capturing
Target → Parent
Parent → Target
Default event propagation phase
Must be enabled when adding the listener
Moves upward
Moves downward
Event Bubbling is the process in which an event travels from the target element toward its parent elements. Event Capturing is the process in which an event travels from the parent elements toward the target element. Both are parts of DOM Event Propagation.
JavaScript Event Delegation
Definition
Event Delegation is a technique where we add one event listener to a parent element instead of adding separate event listeners to every child element.
It works using Event Bubbling.
Simple Example
HTML
HTML
<ul id="items">
  <li>Apple</li>
  <li>Banana</li>
  <li>Mango</li>
</ul>
JavaScript
document.getElementById("items").addEventListener("click", function(event) {
  if (event.target.tagName === "LI") {
    console.log("You clicked: " + event.target.innerText);
  }
});
If you click Apple, the output is:
You clicked: Apple
If you click Banana:
You clicked: Banana
How It Works
The user clicks a child element.
The event bubbles up to the parent.
The parent's event listener receives the event.
event.target identifies the element that was clicked.
The required action is performed.
Advantages
Uses fewer event listeners.
Improves performance for large lists.
Works well with dynamically added elements.
Makes code simpler and easier to maintain.
Example with Dynamic Elements
let list = document.getElementById("items");

list.addEventListener("click", function(event) {
  if (event.target.matches("li")) {
    alert(event.target.innerText);
  }
});
Even if new <li> elements are added later, the parent listener can handle their clicks.
Event Delegation is a technique of attaching a single event listener to a parent element to handle events from its child elements. It uses event bubbling and is useful for improving performance and handling dynamically created elements.
JavaScript Forms and Form Validation
Definition
Form Validation is the process of checking whether the user has entered valid and complete data before submitting a form.
1. Simple HTML Form
HTML
<form id="myForm">
  Name: <input type="text" id="name"><br><br>
  <input type="submit" value="Submit">
</form>
2. JavaScript Form Validation
document.getElementById("myForm").addEventListener("submit", function(event) {

  let name = document.getElementById("name").value;

  if (name === "") {
    alert("Name is required");
    event.preventDefault();
  }
});
Output
If the name field is empty:
Name is required
If the name is entered, the form is submitted.
3. Email Validation
let email = document.getElementById("email").value;

if (!email.includes("@")) {
  alert("Enter a valid email");
}
4. Password Validation
let password = document.getElementById("password").value;

if (password.length < 8) {
  alert("Password must be at least 8 characters");
}
5. Prevent Form Submission
event.preventDefault();
This method stops the form from submitting if the input is invalid.
Types of Validation
Required field validation
Email validation
Password validation
Phone number validation
Number validation
Advantages
Prevents invalid data submission.
Improves user experience.
Reduces server-side errors.
Ensures data accuracy.
Form Validation is the process of checking user input before submitting a form. JavaScript validates fields such as name, email, password, and phone number to ensure the entered data is correct and complete.
JavaScript ES6 Features
Definition
ES6 (ECMAScript 2015) is a major version of JavaScript that introduced many new features to make code simpler, cleaner, and more powerful.
1. let
let is used to declare a variable. Its scope is limited to the block in which it is declared.
let age = 20;
console.log(age);
2. const
const is used to declare a constant. Its value cannot be reassigned.
const PI = 3.14;
console.log(PI);
3. Arrow Function (=>)
Arrow functions provide a shorter syntax for writing functions.
const add = (a, b) => a + b;

console.log(add(10, 20));
Output:
30
4. Template Literals
Template literals use backticks ( ) and allow string interpolation.
let name = "divyapriya";

console.log(`Hello ${name}`);
Output:
Hello divyapriya
5. Destructuring
Destructuring extracts values from arrays or objects.
let person = {
  name: "divyapriya",
  age: 18
};

let { name, age } = person;

console.log(name);
console.log(age);
6. Spread Operator (...)
The spread operator expands an array or object.
let arr1 = [1, 2, 3];
let arr2 = [...arr1, 4, 5];

console.log(arr2);
Output:
[1, 2, 3, 4, 5]
7. Rest Operator (...)
The rest operator collects multiple values into a single array.
function sum(...numbers) {
  console.log(numbers);
}

sum(10, 20, 30);
Output:
[10, 20, 30]
8. Default Parameters
Default parameters provide a default value if no argument is passed.
function greet(name = "Guest") {
  console.log("Hello " + name);
}

greet();
Output:
Hello Guest
9. Modules
ES6 introduced export and import to organize code into separate files.
// math.js
export function add(a, b) {
  return a + b;
}
// main.js
import { add } from "./math.js";

console.log(add(5, 10));
ES6 (ECMAScript 2015) introduced modern JavaScript features such as let, const, arrow functions, template literals, destructuring, spread operator, rest operator, default parameters, and modules. These features make JavaScript code more readable, reusable, and maintainable.
JavaScript BOM (Browser Object Model)
Definition
BOM (Browser Object Model) allows JavaScript to interact with the browser window and browser features.
The main BOM objects are:
window
navigator
location
history
screen
1. Window Object
The window object is the top-level object in the browser.
Example
alert("Welcome to JavaScript");
or
window.alert("Welcome to JavaScript");
2. Navigator Object
The navigator object provides information about the browser.
Example
console.log(navigator.appName);
console.log(navigator.userAgent);
3. Location Object
The location object provides information about the current webpage URL.
Example
console.log(location.href);
To reload the page:
location.reload();
4. History Object
The history object is used to navigate browser history.
Go Back
history.back();
Go Forward
history.forward();
5. Screen Object
The screen object provides information about the user's screen.
Example
console.log(screen.width);
console.log(screen.height);
BOM Objects Summary
Object
Purpose
window
Controls the browser window
navigator
Provides browser information
location
Provides URL information
history
Navigates browser history
screen
Provides screen information
Advantages of BOM
Interacts with the browser.
Gets browser and screen information.
Controls page navigation.
Manages browser windows.
BOM (Browser Object Model) is a collection of browser objects that enables JavaScript to interact with the browser. The main BOM objects are window, navigator, location, history, and screen.
JavaScript AJAX (Asynchronous JavaScript and XML)
Definition
AJAX (Asynchronous JavaScript and XML) is a technique used to send and receive data from a server without reloading the entire web page.
Although AJAX originally used XML, modern applications commonly use JSON for data exchange.
Why Use AJAX?
Updates web pages without refreshing.
Faster user experience.
Reduces server load.
Retrieves data in the background.
1. AJAX using XMLHttpRequest
let xhr = new XMLHttpRequest();

xhr.open("GET", "data.json", true);

xhr.onload = function() {
    if (xhr.status == 200) {
        console.log(xhr.responseText);
    }
};

xhr.send();
2. AJAX using Fetch API (Modern Method)
fetch("data.json")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.log(error));
3. AJAX using Async/Await
async function getData() {
    try {
        let response = await fetch("data.json");
        let data = await response.json();
        console.log(data);
    } catch (error) {
        console.log(error);
    }
}

getData();
AJAX Flow
User performs an action.
JavaScript sends a request to the server.
The server processes the request.
The server sends data back.
JavaScript updates the webpage without reloading it.
Advantages
No full page refresh.
Faster performance.
Better user experience.
Saves bandwidth.
Supports real-time updates.
Disadvantages
Depends on JavaScript being enabled.
More complex than simple page loads.
Debugging can be more difficult.

AJAX (Asynchronous JavaScript and XML) is a technique that allows JavaScript to communicate with a server and update parts of a webpage without reloading the entire page. Modern AJAX applications commonly use the Fetch API and JSON.
JavaScript Fetch API
Definition
The Fetch API is a modern JavaScript API used to send HTTP requests and receive responses from a server. It is promise-based and is commonly used to communicate with REST APIs.
HTTP Methods
GET → Retrieve data
POST → Send new data
PUT → Update existing data
DELETE → Delete data
1. GET Request
Used to retrieve data from a server.
fetch("https://jsonplaceholder.typicode.com/users")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.log(error));
2. POST Request
Used to send new data to a server.
fetch("https://jsonplaceholder.typicode.com/posts", {
  method: "POST",
  headers: {
    "Content-Type": "application/json"
  },
  body: JSON.stringify({
    title: "JavaScript",
    body: "Fetch API Example"
  })
})
.then(response => response.json())
.then(data => console.log(data));
3. PUT Request
Used to update existing data.
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "PUT",
  headers: {
    "Content-Type": "application/json"
  },
  body: JSON.stringify({
    title: "Updated Title"
  })
})
.then(response => response.json())
.then(data => console.log(data));
4. DELETE Request
Used to delete data.
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "DELETE"
})
.then(response => console.log("Data Deleted"));
5. Fetch API using Async/Await
async function getUsers() {
  try {
    const response = await fetch("https://jsonplaceholder.typicode.com/users");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.log(error);
  }
}

getUsers();
Advantages of Fetch API
Modern and easy to use.
Promise-based.
Supports Async/Await.
Supports all HTTP methods.
Better than XMLHttpRequest for many use cases.
The Fetch API is a modern JavaScript API used to send HTTP requests and receive responses from a server. It supports methods such as GET, POST, PUT, and DELETE and works with Promises and Async/Await.
REST API
Definition
REST API (Representational State Transfer Application Programming Interface) is a set of rules that allows two applications (such as a frontend and a backend) to communicate over the internet using HTTP.
For example:
A website requests user data from a server.
The server sends the data back in JSON format.
REST API Architecture
Client (Browser)
       │
       │ HTTP Request
       ▼
REST API Server
       │
       │ JSON Response
       ▼
Client (Browser)
HTTP Methods
1. GET
Used to retrieve data.
Example:
GET /users
2. POST
Used to create new data.
Example:
POST /users
3. PUT
Used to update existing data.
Example:
PUT /users/1
4. DELETE
Used to delete data.
Example:
DELETE /users/1
Request Structure
A request contains:
URL (Endpoint)
HTTP Method
Headers
Body (for POST/PUT requests)
Example:
POST /users
Content-Type: application/json

{
  "name": "Gyan",
  "age": 20
}
Response Structure
The server sends:
Status Code
Headers
Body (usually JSON)
Example:
{
  "id": 1,
  "name": "Gyan",
  "age": 20
}
Common HTTP Status Codes
Status Code
Meaning
200 OK
Request successful
201 Created
Resource created successfully
400 Bad Request
Invalid request
401 Unauthorized
Authentication required
403 Forbidden
Access denied
404 Not Found
Resource not found
500 Internal Server Error
Server error
Advantages of REST API
Fast and lightweight.
Uses JSON for data exchange.
Platform independent.
Easy to integrate with web and mobile applications.
Widely used in modern web development.
A REST API is an interface that allows applications to communicate over HTTP. It uses methods such as GET, POST, PUT, and DELETE to perform operations on resources and commonly exchanges data in JSON format.
Node.js Introduction
1. What is Node.js?
Node.js is a JavaScript runtime environment that allows us to run JavaScript outside the browser.
Normally, JavaScript runs in a browser like Chrome. With Node.js, we can use JavaScript to build backend/server-side applications.
Simple idea
Browser
   ↓
Frontend → HTML + CSS + JavaScript
   ↓
Backend → Node.js
   ↓
Database → MongoDB / MySQL
2. Why Use Node.js?
Node.js is commonly used to build:
Web servers
REST APIs
Backend applications
Real-time applications
Chat applications
Full-stack applications
3. Important Features
Single-threaded
Node.js uses a single main JavaScript thread with an event-driven architecture.
Non-blocking
It can handle many I/O operations without waiting for each one to finish before handling other work.
Event-driven
Node.js uses events and callbacks/promises to handle asynchronous operations.
Fast
Node.js uses Google's V8 JavaScript engine.
NPM
Node.js comes with npm (Node Package Manager), which allows developers to install and manage packages.
4. Check Node.js Installation
Open VS Code → Terminal and type:
node --version
Example:
v22.x.x
Then check npm:
npm --version
5. Create Your First Node.js Program
Create a file called:
app.js
Write:
console.log("Hello Node.js");
Run it in the terminal:
node app.js
Output
Hello Node.js
6. Create a Node.js Project
Open your project folder in VS Code and run:
npm init -y
This creates:
package.json
The package.json file contains information about your Node.js project and its dependencies/scripts.
7. Simple Node.js Server
Create server.js:
const http = require("http");

const server = http.createServer((req, res) => {
    res.end("Hello from Node.js Server");
});

server.listen(3000, () => {
    console.log("Server running on port 3000");
});
Run:
node server.js
You should see:
Server running on port 3000
Now open your browser and enter:
http://localhost:3000
You should see:
Hello from Node.js Server

Node.js is an open-source, cross-platform JavaScript runtime environment that allows JavaScript to run outside the browser. It uses the V8 engine and is commonly used for building servers, REST APIs, and backend applications.

NPM (Node Package Manager)
1. What is NPM?
NPM stands for Node Package Manager. It is the default package manager for Node.js.
It is used to:
Install packages
Manage dependencies
Run project scripts
Share JavaScript packages
2. Check NPM Version
Open the VS Code terminal and type:
npm --version
Example output:
10.x.x
3. Create a Node.js Project
Create a folder for your project and open it in VS Code.
Then run:
npm init -y
This creates a file called:
package.json
4. What is package.json?
package.json contains important information about your Node.js project.
Example:
{
  "name": "my-project",
  "version": "1.0.0",
  "main": "app.js"
}
It can also contain:
Project name
Version
Scripts
Dependencies
Development dependencies
5. Install a Package
For example, install Express:
npm install express
After installation, you will normally see:
node_modules
package-lock.json
package.json
6. node_modules
node_modules contains the packages installed for your project and their dependencies.
⚠️ Usually, you do not manually edit files inside node_modules.
7. package-lock.json
package-lock.json records the specific dependency versions installed for the project.
It helps make installations more consistent across environments.
8. Install a Development Dependency
Some packages are needed mainly during development.
Example:
npm install --save-dev nodemon
This adds the package under devDependencies in package.json.
9. Uninstall a Package
npm uninstall express
This removes the package from the project.
10. Useful NPM Commands
Command
Purpose
npm init -y
Create a Node.js project
npm install express
Install Express
npm uninstall express
Remove Express
npm install
Install dependencies from package.json
npm install --save-dev nodemon
Install a development dependency
npm --version
Check npm version
Simple Flow
Create Folder
     ↓
npm init -y
     ↓
package.json
     ↓
npm install package-name
     ↓
node_modules
     ↓
Use package in your program
NPM (Node Package Manager) is the package manager for Node.js. It is used to install, update, remove, and manage packages and project dependencies. Important files include package.json, package-lock.json, and the node_modules folder.
Node.js Modules
1. What is a Module?
A module is a separate file containing reusable code.
Instead of putting an entire application into one file, we can divide it into multiple files and reuse the required code.
Example
project/
│
├── app.js
└── math.js
2. CommonJS Modules
Node.js traditionally uses CommonJS modules with:
module.exports
require()
Step 1: Create math.js
function add(a, b) {
  return a + b;
}

module.exports = add;
Step 2: Use it in app.js
const add = require("./math");

console.log(add(10, 20));
Output
30
3. Exporting Multiple Functions
math.js
function add(a, b) {
  return a + b;
}

function subtract(a, b) {
  return a - b;
}

module.exports = {
  add,
  subtract
};
app.js
const math = require("./math");

console.log(math.add(10, 20));
console.log(math.subtract(20, 10));
Output
30
10
4. ES Modules
Modern JavaScript also supports ES Modules, using:
export
import
math.js
export function add(a, b) {
  return a + b;
}
app.js
import { add } from "./math.js";

console.log(add(10, 20));
For Node.js to treat .js files as ES modules, you can configure package.json with:
{
  "type": "module"
}
5. Why Use Modules?
Modules help you:
Reuse code
Organize large projects
Reduce code duplication
Make programs easier to maintain
Separate different responsibilities
CommonJS vs ES Modules
CommonJS
ES Modules
require()
import
module.exports
export
Traditional Node.js module system
Modern JavaScript module system
A Node.js module is a separate file containing reusable code. Node.js supports CommonJS modules using require() and module.exports, as well as ES Modules using import and export
Node.js File System (fs) Module
1. What is the fs Module?
The File System (fs) module is a built-in Node.js module used to work with files and folders.
It can be used to:
Create files
Read files
Write files
Update files
Delete files
Rename files
You don't need to install it separately.
2. Import the fs Module
CommonJS
const fs = require("fs");
3. Write to a File
writeFile() creates a file or replaces its contents.
const fs = require("fs");

fs.writeFile("message.txt", "Hello Node.js", (err) => {
  if (err) throw err;
  console.log("File written successfully");
});
After running the program, message.txt will contain:
Hello Node.js
4. Read a File
const fs = require("fs");

fs.readFile("message.txt", "utf8", (err, data) => {
  if (err) throw err;
  console.log(data);
});
Output
Hello Node.js
5. Add Data to a File
Use appendFile() to add content without replacing the existing content.
const fs = require("fs");

fs.appendFile("message.txt", "\nWelcome!", (err) => {
  if (err) throw err;
  console.log("Data added");
});
6. Delete a File
Use unlink().
const fs = require("fs");

fs.unlink("message.txt", (err) => {
  if (err) throw err;
  console.log("File deleted");
});
7. Rename a File
Use rename().
const fs = require("fs");

fs.rename("old.txt", "new.txt", (err) => {
  if (err) throw err;
  console.log("File renamed");
});
Common fs Methods
Method
Purpose
writeFile()
Create/write a file
readFile()
Read a file
appendFile()
Add data
unlink()
Delete a file
rename()
Rename a file
The Node.js fs module is a built-in module used to interact with the file system. It provides methods such as readFile(), writeFile(), appendFile(), unlink(), and rename().
Express.js Introduction
1. What is Express.js?
Express.js is a lightweight and popular web framework for Node.js. It makes it easier to build:
Web servers
REST APIs
Backend applications
Routes
Middleware
Instead of writing lots of code using Node's basic http module, Express provides simpler methods.
2. Install Express
First create a Node.js project:
npm init -y
Then install Express:
npm install express
3. Create Your First Express Server
Create a file:
server.js
Write:
const express = require("express");

const app = express();

app.get("/", (req, res) => {
  res.send("Hello Express.js");
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
4. Run the Server
Open the VS Code terminal:
node server.js
You should see:
Server running on port 3000
Open your browser:
http://localhost:3000
Output:
Hello Express.js
5. Creating Routes
Routes define how the server responds to different URLs.
app.get("/", (req, res) => {
  res.send("Home Page");
});

app.get("/about", (req, res) => {
  res.send("About Page");
});

app.get("/contact", (req, res) => {
  res.send("Contact Page");
});
Now:
/          → Home Page
/about     → About Page
/contact   → Contact Page
6. HTTP Methods in Express
Express supports common HTTP methods:
app.get("/users", (req, res) => {
  res.send("Get Users");
});

app.post("/users", (req, res) => {
  res.send("Create User");
});

app.put("/users/1", (req, res) => {
  res.send("Update User");
});

app.delete("/users/1", (req, res) => {
  res.send("Delete User");
});
7. req and res
req
req represents the client's request.
req.params
req.query
req.body
res
res represents the server's response.
res.send()
res.json()
res.status()
Example:
app.get("/hello", (req, res) => {
  res.send("Hello!");
});
8. Why Express?
Node.js HTTP
Express.js
More manual code
Simpler syntax
Basic HTTP functionality
Routing and middleware support
More work for larger APIs
Easier API development
Built into Node.js
Installed as a package
Express.js is a web framework for Node.js used to build web servers and REST APIs easily. It provides convenient features such as routing, middleware, request handling, and response handling.
Express.js Middleware
1. What is Middleware?
Middleware is a function that runs between the incoming request and the final response.
It can:
Check requests
Log information
Modify request/response objects
Perform authentication/authorization checks
Handle errors
Pass control to the next middleware or route
Basic Flow
Client
  ↓
Request
  ↓
Middleware
  ↓
Route Handler
  ↓
Response
  ↓
Client
2. app.use()
app.use() is commonly used to register middleware.
const express = require("express");

const app = express();

app.use((req, res, next) => {
  console.log("Middleware executed");
  next();
});

app.get("/", (req, res) => {
  res.send("Home Page");
});

app.listen(3000);
What is next()?
next() tells Express:
"This middleware has finished. Continue to the next middleware or route."
3. Logger Middleware
A simple middleware can log requests.
app.use((req, res, next) => {
  console.log(req.method, req.url);
  next();
});
If you visit:
http://localhost:3000/about
You might see:
GET /about
4. Built-in Middleware
Express provides some built-in middleware.
express.json()
Used to parse incoming JSON request bodies.
app.use(express.json());
For example, a client can send:
{
  "name": "Gyan",
  "branch": "CSE"
}
Then in a route:
app.post("/users", (req, res) => {
  console.log(req.body);
  res.json(req.body);
});
5. Static Middleware
Used to serve files such as HTML, CSS, JavaScript, and images.
app.use(express.static("public"));
If your project contains:
project/
│
├── server.js
└── public/
    └── index.html
Express can serve files from the public folder.
6. Multiple Middleware Functions
You can use multiple middleware functions.
app.use((req, res, next) => {
  console.log("First middleware");
  next();
});

app.use((req, res, next) => {
  console.log("Second middleware");
  next();
});

app.get("/", (req, res) => {
  res.send("Home");
});
7. Middleware with a Specific Route
Middleware can also be applied to a particular route.
function checkUser(req, res, next) {
  console.log("Checking user");
  next();
}

app.get("/profile", checkUser, (req, res) => {
  res.send("Profile Page");
});
Types of Middleware
Type
Example
Application-level
app.use()
Router-level
router.use()
Built-in
express.json()
Third-party
cors, morgan
Error-handling
(err, req, res, next)
Express middleware is a function that executes during the request-response cycle. It can perform tasks such as logging, parsing JSON, authentication, and error handling. Middleware uses the next() function to pass control to the next middleware or route.

Express.js Routing in Detail
Routing means defining how an Express application responds to different URLs and HTTP methods.
1. Basic Route
app.get("/", (req, res) => {
  res.send("Home Page");
});
Here:
GET → HTTP method
/ → route/path
req → request
res → response
2. Route Parameters
Route parameters are values included directly in the URL.
app.get("/users/:id", (req, res) => {
  res.send("User ID: " + req.params.id);
});
If you open:
http://localhost:3000/users/101
Output:
User ID: 101
You can access it using:
req.params.id
3. Multiple Route Parameters
app.get("/users/:userId/posts/:postId", (req, res) => {
  res.json({
    user: req.params.userId,
    post: req.params.postId
  });
});
URL:
/users/10/posts/25
4. Query Parameters
Query parameters come after ? in a URL.
Example:
/users?name=Gyan&branch=CSE
Access them using:
app.get("/users", (req, res) => {
  console.log(req.query.name);
  console.log(req.query.branch);

  res.send("Data received");
});
Output:
Gyan
CSE
Difference
/users/101
101 → Route parameter
/users?name=Gyan
name=Gyan → Query parameter
5. Request Body
For POST requests, data is commonly sent in the request body.
First:
app.use(express.json());
Then:
app.post("/users", (req, res) => {
  console.log(req.body);

  res.json({
    message: "User created",
    user: req.body
  });
});
Example JSON sent by the client:
{
  "name": "Gyan",
  "branch": "CSE"
}
6. Route Status Code
app.get("/users", (req, res) => {
  res.status(200).json({
    message: "Users retrieved"
  });
});
For creating data:
res.status(201).json({
  message: "User created"
});
7. Router
For larger applications, routes can be separated into different files.
Example:
project/
│
├── server.js
└── routes/
    └── userRoutes.js
userRoutes.js
const express = require("express");

const router = express.Router();

router.get("/", (req, res) => {
  res.send("All Users");
});

router.get("/:id", (req, res) => {
  res.send("User ID: " + req.params.id);
});

module.exports = router;
server.js
const express = require("express");
const userRoutes = require("./routes/userRoutes");

const app = express();

app.use("/users", userRoutes);

app.listen(3000, () => {
  console.log("Server running");
});
Now:
/users       → All Users
/users/101   → User ID: 101
Express routing defines how an application responds to different URLs and HTTP methods. Express supports GET, POST, PUT, DELETE, route parameters using req.params, query parameters using req.query, and request-body data using req.body.
Express.js CRUD Operations
CRUD stands for:
C → Create
R → Read
U → Update
D → Delete
CRUD is one of the most important concepts when building REST APIs.
1. Create → POST
Used to create new data.
app.post("/users", (req, res) => {
  const user = req.body;

  res.status(201).json({
    message: "User created",
    user: user
  });
});
2. Read → GET
Used to retrieve data.
app.get("/users", (req, res) => {
  res.json({
    message: "All users"
  });
});
To get one user:
app.get("/users/:id", (req, res) => {
  res.json({
    userId: req.params.id
  });
});
3. Update → PUT
Used to update existing data.
app.put("/users/:id", (req, res) => {
  const id = req.params.id;
  const updatedUser = req.body;

  res.json({
    message: "User updated",
    id: id,
    user: updatedUser
  });
});
4. Delete → DELETE
Used to delete data.
app.delete("/users/:id", (req, res) => {
  const id = req.params.id;

  res.json({
    message: "User deleted",
    id: id
  });
});
Complete CRUD Example
const express = require("express");

const app = express();

app.use(express.json());

app.post("/users", (req, res) => {
  res.status(201).json({
    message: "User created",
    user: req.body
  });
});

app.get("/users", (req, res) => {
  res.json({
    message: "Users retrieved"
  });
});

app.put("/users/:id", (req, res) => {
  res.json({
    message: "User updated",
    id: req.params.id,
    user: req.body
  });
});

app.delete("/users/:id", (req, res) => {
  res.json({
    message: "User deleted",
    id: req.params.id
  });
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
CRUD Summary
Operation
HTTP Method
Example
Create
POST
/users
Read
GET
/users
Update
PUT
/users/101
Delete
DELETE
/users/101
Important Point
This example only demonstrates the API structure. The data isn't permanently stored yet.
MongoDB Introduction
1. What is MongoDB?
MongoDB is a NoSQL database used to store and manage data.
Unlike traditional databases such as MySQL, MongoDB stores data in documents rather than rows and columns.
Simple Full-Stack Flow
Frontend
   ↓
JavaScript
   ↓
Express.js
   ↓
Node.js
   ↓
MongoDB
2. MongoDB Document
MongoDB stores data in a format similar to JSON.
Example:
{
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
MongoDB actually stores documents in BSON, a binary representation of JSON-like data.
3. Database
A database is a container for collections.
Example:
collegeDB
4. Collection
A collection is similar to a table in a relational database.
Example:
collegeDB
   └── students
5. Document
A document is similar to a row in a relational database.
Example:
{
  "name": "Gyan",
  "branch": "CSE",
  "year": 3
}
6. MongoDB vs MySQL
MongoDB
MySQL
NoSQL database
Relational database
Collection
Table
Document
Row
Field
Column
BSON/JSON-like documents
Tables with rows and columns
Flexible schema
Structured schema
7. Basic MongoDB Operations
MongoDB uses CRUD operations.
Insert
db.students.insertOne({
  name: "Gyan",
  branch: "CSE"
});
Find
db.students.find();
Update
db.students.updateOne(
  { name: "Gyan" },
  { $set: { branch: "IT" } }
);
Delete
db.students.deleteOne({
  name: "Gyan"
});
8. Important MongoDB Terms
Database
Stores collections.
Collection
Stores documents.
Document
Stores individual records.
Field
A key-value pair inside a document.
_id
MongoDB automatically gives each document a unique identifier called _id.
Example:
{
  "_id": "unique-id",
  "name": "Gyan"
}
9. MongoDB Compass
MongoDB Compass is a graphical user interface (GUI) for MongoDB.
You can use it to:
Create databases
Create collections
Insert documents
View documents
Update documents
Delete documents
Run queries
MongoDB is a popular NoSQL database that stores data as flexible, JSON-like documents. A MongoDB database contains collections, and collections contain documents. MongoDB supports CRUD operations and is commonly used with Node.js and Express.js.
MongoDB Installation & Compass — Step by Step
Since you're learning Node.js + Express + MongoDB, let's set up MongoDB first.
1. Download MongoDB
Go to the official MongoDB website:
https://www.mongodb.com/try/download/community⁠�
Choose:
Version: Current stable version
Platform: Windows
Package: MSI
Download the installer.
2. Install MongoDB
Open the downloaded .msi file.
Follow these steps:
Click Next.
Accept the license agreement.
Click Next.
Select Complete installation.
Keep the default installation settings.
If you see Install MongoD as a Service, keep it selected.
Click Next.
Click Install.
Wait for installation to finish.
Click Finish.
3. Install MongoDB Compass
During MongoDB installation, you may see an option to install MongoDB Compass.
Keep it selected and continue.
Compass gives you a graphical interface to work with MongoDB.
4. Open MongoDB Compass
Open Windows Search and type:
MongoDB Compass
Open it.
You will see a connection screen.
For a local MongoDB server, the connection is commonly:
mongodb://localhost:27017
Click Connect.
5. Create Your First Database
In MongoDB Compass:
Click Create Database.
Enter database name:
collegeDB
Enter collection name:
students
Click Create Database.
Now you have:
collegeDB
   └── students
6. Insert a Document
Open:
collegeDB → students
Click Add Data → Insert Document.
Enter:
{
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
Click Insert.
7. View the Document
After inserting it, Compass will display your document.
MongoDB will automatically add an _id field.
Example:
{
  "_id": "...",
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
8. Check MongoDB from Terminal
Open Command Prompt or PowerShell.
Try:
mongosh
If MongoDB Shell is installed and available, you should enter the MongoDB shell.
Then:
show dbs
To use your database:
use collegeDB
To see collections:
show collections
You should see:
students
9. Find Documents
Run:
db.students.find()
You should see the student document you inserted.
10. Basic MongoDB Commands
show dbs
Shows databases.
use collegeDB
Selects a database.
show collections
Shows collections.
db.students.find()
Shows documents.
Complete Structure
MongoDB
   │
   └── collegeDB
          │
          └── students
                 │
                 ├── Document 1
                 ├── Document 2
                 └── Document 3
MongoDB Compass is a graphical user interface for MongoDB. It allows developers to connect to MongoDB, create databases and collections, and perform CRUD operations without using only the command line.
Connecting MongoDB with Node.js & Express
Now we'll connect the Express backend to MongoDB. A popular library for this is Mongoose.
1. Install Mongoose
Open your project folder in VS Code Terminal:
npm install mongoose
2. Project Structure
Create this structure:
my-project/
│
├── server.js
├── package.json
└── node_modules/
3. Import Mongoose
In server.js:
const express = require("express");
const mongoose = require("mongoose");

const app = express();

app.use(express.json());
4. Connect to MongoDB
For a local MongoDB server:
mongoose.connect("mongodb://127.0.0.1:27017/collegeDB")
  .then(() => {
    console.log("MongoDB connected");
  })
  .catch((error) => {
    console.log("Connection failed:", error);
  });
Here:
127.0.0.1 → Your computer
27017      → MongoDB's default port
collegeDB  → Database name
5. Create a Mongoose Schema
A Schema describes the structure of the documents your application expects.
const studentSchema = new mongoose.Schema({
  name: String,
  age: Number,
  branch: String
});
6. Create a Model
A Model is used to interact with MongoDB documents.
const Student = mongoose.model("Student", studentSchema);
7. Create a POST API
app.post("/students", async (req, res) => {
  try {
    const student = new Student(req.body);

    const savedStudent = await student.save();

    res.status(201).json(savedStudent);
  } catch (error) {
    res.status(500).json({
      message: "Error creating student"
    });
  }
});
You can send:
{
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
8. Create a GET API
app.get("/students", async (req, res) => {
  try {
    const students = await Student.find();

    res.json(students);
  } catch (error) {
    res.status(500).json({
      message: "Error getting students"
    });
  }
});
This retrieves students from MongoDB.
9. Start the Server
At the bottom of server.js:
app.listen(3000, () => {
  console.log("Server running on port 3000");
});
Run:
node server.js
You should see:
MongoDB connected
Server running on port 3000
10. Complete Example
const express = require("express");
const mongoose = require("mongoose");

const app = express();

app.use(express.json());

mongoose.connect("mongodb://127.0.0.1:27017/collegeDB")
  .then(() => console.log("MongoDB connected"))
  .catch(error => console.log(error));

const studentSchema = new mongoose.Schema({
  name: String,
  age: Number,
  branch: String
});

const Student = mongoose.model("Student", studentSchema);

app.post("/students", async (req, res) => {
  try {
    const student = new Student(req.body);
    const savedStudent = await student.save();

    res.status(201).json(savedStudent);
  } catch (error) {
    res.status(500).json({ message: "Error creating student" });
  }
});

app.get("/students", async (req, res) => {
  try {
    const students = await Student.find();
    res.json(students);
  } catch (error) {
    res.status(500).json({ message: "Error getting students" });
  }
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
Overall Flow
Client
  ↓
Express.js
  ↓
Mongoose
  ↓
MongoDB
  ↓
Database
Important Terms
Mongoose → Helps Node.js applications work with MongoDB.
Schema → Defines the expected document structure.
Model → Provides methods to create, read, update, and delete documents.
MongoDB → Stores the actual data.
Mongoose CRUD Operations
Now let's learn how to perform Create, Read, Update, and Delete (CRUD) operations using Mongoose + Express + MongoDB.
1. Create — POST
Create a new student.
app.post("/students", async (req, res) => {
  try {
    const student = await Student.create(req.body);

    res.status(201).json(student);
  } catch (error) {
    res.status(500).json({
      message: "Error creating student"
    });
  }
});
Request Body
{
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
2. Read — GET
Get All Students
app.get("/students", async (req, res) => {
  try {
    const students = await Student.find();

    res.json(students);
  } catch (error) {
    res.status(500).json({
      message: "Error getting students"
    });
  }
});
Get One Student
app.get("/students/:id", async (req, res) => {
  try {
    const student = await Student.findById(req.params.id);

    res.json(student);
  } catch (error) {
    res.status(500).json({
      message: "Error getting student"
    });
  }
});
The :id comes from the URL.
Example:
/students/64abc123...
Access it using:
req.params.id
3. Update — PUT
Update an existing student.
app.put("/students/:id", async (req, res) => {
  try {
    const student = await Student.findByIdAndUpdate(
      req.params.id,
      req.body,
      { new: true }
    );

    res.json(student);
  } catch (error) {
    res.status(500).json({
      message: "Error updating student"
    });
  }
});
Why { new: true }?
It tells Mongoose to return the updated document.
4. Delete — DELETE
Delete a student.
app.delete("/students/:id", async (req, res) => {
  try {
    await Student.findByIdAndDelete(req.params.id);

    res.json({
      message: "Student deleted successfully"
    });
  } catch (error) {
    res.status(500).json({
      message: "Error deleting student"
    });
  }
});
Complete CRUD Flow
             MongoDB
                ↑
                │
             Mongoose
                ↑
                │
             Express
                ↑
                │
              Client
API Endpoints
Operation
Method
Endpoint
Create
POST
/students
Read all
GET
/students
Read one
GET
/students/:id
Update
PUT
/students/:id
Delete
DELETE
/students/:id
Important Mongoose Methods
Student.create()
Creates a document.
Student.find()
Finds multiple documents.
Student.findById()
Finds one document by ID.
Student.findByIdAndUpdate()
Updates a document.
Student.findByIdAndDelete()
Deletes a document.
Mongoose CRUD operations allow a Node.js/Express application to interact with MongoDB. create() is used to insert data, find() and findById() retrieve data, findByIdAndUpdate() modifies data, and findByIdAndDelete() removes data.
REST API Testing with Postman
Postman is a tool used to test APIs without creating a frontend.
You can test your Node.js + Express + MongoDB backend using Postman.
1. Install Postman
Go to:
https://www.postman.com/downloads/⁠�
Download and install Postman for your computer.
2. Start Your Backend
Open your project in VS Code.
Run:
node server.js
You should see something like:
MongoDB connected
Server running on port 3000
Your API base URL is:
http://localhost:3000
3. Test GET Request
Open Postman.
Select:
GET
Enter:
http://localhost:3000/students
Click Send.
If your API is working, you should receive JSON data.
Example:
[
  {
    "_id": "123",
    "name": "Gyan",
    "age": 20,
    "branch": "CSE"
  }
]
4. Test POST Request
Select:
POST
Enter:
http://localhost:3000/students
Go to:
Body → raw → JSON
Enter:
{
  "name": "Gyan",
  "age": 20,
  "branch": "CSE"
}
Click Send.
You should receive the newly created document.
5. Test PUT Request
Suppose the student ID is:
123
Select:
PUT
URL:
http://localhost:3000/students/123
Body:
{
  "name": "Gyan",
  "age": 21,
  "branch": "IT"
}
Click Send.
The student information should be updated.
6. Test DELETE Request
Select:
DELETE
URL:
http://localhost:3000/students/123
Click Send.
If successful, you might receive:
{
  "message": "Student deleted successfully"
}
7. CRUD Testing Summary
Operation
Method
URL
Create
POST
/students
Read
GET
/students
Read one
GET
/students/:id
Update
PUT
/students/:id
Delete
DELETE
/students/:id
8. Common Problems
Cannot GET /students
Check:
Server is running.
URL is correct.
HTTP method is correct.
Route is defined correctly.
ECONNREFUSED
Usually means your server isn't running or you're using the wrong port.
Check:
node server.js
MongoDB connection error
Check:
MongoDB is running.
Connection URL is correct.
Port is correct.
Example:
mongodb://127.0.0.1:27017/collegeDB
API Testing Flow
Postman
   ↓
HTTP Request
   ↓
Express Route
   ↓
Mongoose
   ↓
MongoDB
   ↓
Response
   ↓
Postman
Postman is an API testing tool used to send HTTP requests and inspect server responses. It can be used to test REST API operations such as GET, POST, PUT, and DELETE without building a frontend.
   Environment Variables with .env
When building Node.js applications, we often have configuration values such as:
MongoDB connection URL
Server port
API keys
Application settings
Instead of writing these directly in the source code, we can store them in environment variables.
1. What is .env?
.env is a file commonly used to store configuration values.
Example:
PORT=3000
MONGODB_URI=mongodb://127.0.0.1:27017/collegeDB
2. Install dotenv
In your project terminal:
npm install dotenv
3. Create .env
Your project can look like:
my-project/
│
├── server.js
├── .env
├── package.json
└── node_modules/
Inside .env:
PORT=3000
MONGODB_URI=mongodb://127.0.0.1:27017/collegeDB
4. Load Environment Variables
In server.js:
require("dotenv").config();
Then access them through:
process.env.PORT
and:
process.env.MONGODB_URI
5. Complete Example
const express = require("express");
const mongoose = require("mongoose");
require("dotenv").config();

const app = express();

app.use(express.json());

mongoose.connect(process.env.MONGODB_URI)
  .then(() => {
    console.log("MongoDB connected");
  })
  .catch((error) => {
    console.log("MongoDB connection error:", error);
  });

app.get("/", (req, res) => {
  res.send("Server is working");
});

const PORT = process.env.PORT || 3000;

app.listen(PORT, () => {
  console.log(`Server running on port ${PORT}`);
});
6. Why Use .env?
Instead of:
mongoose.connect("mongodb://127.0.0.1:27017/collegeDB");
you can use:
mongoose.connect(process.env.MONGODB_URI);
This makes configuration easier to change between environments.
7. Important Security Rule
Don't commit sensitive .env files to a public GitHub repository.
Create a .gitignore file:
node_modules/
.env
This tells Git to ignore those files.
⚠️ Never put real passwords, private API keys, or database credentials directly into publicly shared source code.
Flow
.env
 ↓
dotenv
 ↓
process.env
 ↓
Node.js Application
An environment variable is a configuration value provided outside the application code. In Node.js, the dotenv package can load variables from a .env file, and they can be accessed using process.env. This is commonly used for ports, database URLs, and other configuration values.
Authentication and Authorization
These are important concepts in backend development.
1. Authentication
Authentication means checking who the user is.
Example:
User enters:
Email + Password
       ↓
Server verifies details
       ↓
Correct → User authenticated
Example: Logging into a website.
2. Authorization
Authorization means checking what an authenticated user is allowed to do.
Example:
User → Logged in
       ↓
Is user an Admin?
       ↓
Yes → Can access admin page
No  → Access denied
Simple Difference
Authentication
Authorization
Who are you?
What can you access?
Happens during login
Happens when accessing resources
Verifies identity
Checks permissions
3. Passwords
Passwords should not be stored as plain text in a database.
❌ Bad:
{
  "email": "user@example.com",
  "password": "mypassword"
}
Instead, applications normally store a secure password hash.
A common Node.js package is:
npm install bcrypt
Example:
const bcrypt = require("bcrypt");

const hashedPassword = await bcrypt.hash("mypassword", 10);

console.log(hashedPassword);
When logging in, bcrypt.compare() can check a password against its stored hash.
4. JWT
JWT (JSON Web Token) is commonly used to represent authenticated user information between a client and server.
Install:
npm install jsonwebtoken
Create a token:
const jwt = require("jsonwebtoken");

const token = jwt.sign(
  { userId: "123" },
  process.env.JWT_SECRET,
  { expiresIn: "1h" }
);

console.log(token);
The secret should be stored securely, for example in .env:
JWT_SECRET=your-secret-value
5. JWT Authentication Flow
User
 ↓
Login
 ↓
Server verifies credentials
 ↓
JWT generated
 ↓
Client stores token
 ↓
Client sends token with protected requests
 ↓
Server verifies token
 ↓
Access granted / denied
6. Protected Route
A middleware can verify a JWT before allowing access.
function authenticateToken(req, res, next) {
  const authHeader = req.headers.authorization;

  const token = authHeader && authHeader.split(" ")[1];

  if (!token) {
    return res.status(401).json({
      message: "Authentication required"
    });
  }

  try {
    const user = jwt.verify(token, process.env.JWT_SECRET);

    req.user = user;
    next();
  } catch (error) {
    return res.status(403).json({
      message: "Invalid or expired token"
    });
  }
}
Then protect a route:
app.get("/profile", authenticateToken, (req, res) => {
  res.json({
    message: "Welcome to your profile",
    user: req.user
  });
});
7. HTTP Status Codes
For authentication:
401 → Authentication required/invalid credentials
403 → Authenticated but not allowed to access the resource
Authentication verifies the identity of a user, while authorization determines what that authenticated user is allowed to access. In Node.js applications, passwords are securely hashed using tools such as bcrypt, and JWT is commonly used for token-based authentication.
Authentication and Authorization
These are important concepts in backend development.
1. Authentication
Authentication means checking who the user is.
Example:
User enters:
Email + Password
       ↓
Server verifies details
       ↓
Correct → User authenticated
Example: Logging into a website.
2. Authorization
Authorization means checking what an authenticated user is allowed to do.
Example:
User → Logged in
       ↓
Is user an Admin?
       ↓
Yes → Can access admin page
No  → Access denied
Simple Difference
Authentication
Authorization
Who are you?
What can you access?
Happens during login
Happens when accessing resources
Verifies identity
Checks permissions
3. Passwords
Passwords should not be stored as plain text in a database.
❌ Bad:
{
  "email": "user@example.com",
  "password": "mypassword"
}
Instead, applications normally store a secure password hash.
A common Node.js package is:
npm install bcrypt
Example:
const bcrypt = require("bcrypt");

const hashedPassword = await bcrypt.hash("mypassword", 10);

console.log(hashedPassword);
When logging in, bcrypt.compare() can check a password against its stored hash.
4. JWT
JWT (JSON Web Token) is commonly used to represent authenticated user information between a client and server.
Install:
npm install jsonwebtoken
Create a token:
const jwt = require("jsonwebtoken");

const token = jwt.sign(
  { userId: "123" },
  process.env.JWT_SECRET,
  { expiresIn: "1h" }
);

console.log(token);
The secret should be stored securely, for example in .env:
JWT_SECRET=your-secret-value
5. JWT Authentication Flow
User
 ↓
Login
 ↓
Server verifies credentials
 ↓
JWT generated
 ↓
Client stores token
 ↓
Client sends token with protected requests
 ↓
Server verifies token
 ↓
Access granted / denied
6. Protected Route
A middleware can verify a JWT before allowing access.
function authenticateToken(req, res, next) {
  const authHeader = req.headers.authorization;

  const token = authHeader && authHeader.split(" ")[1];

  if (!token) {
    return res.status(401).json({
      message: "Authentication required"
    });
  }

  try {
    const user = jwt.verify(token, process.env.JWT_SECRET);

    req.user = user;
    next();
  } catch (error) {
    return res.status(403).json({
      message: "Invalid or expired token"
    });
  }
}
Then protect a route:
app.get("/profile", authenticateToken, (req, res) => {
  res.json({
    message: "Welcome to your profile",
    user: req.user
  });
});
7. HTTP Status Codes
For authentication:
401 → Authentication required/invalid credentials
403 → Authenticated but not allowed to access the resource
Authentication verifies the identity of a user, while authorization determines what that authenticated user is allowed to access. In Node.js applications, passwords are securely hashed using tools such as bcrypt, and JWT is commonly used for token-based authentication.
JWT Login & Registration System
Now let's understand how a typical registration + login system works using:
Node.js + Express + MongoDB + Mongoose + bcrypt + JWT
1. Overall Flow
Registration
User
 ↓
Email + Password
 ↓
Hash Password
 ↓
MongoDB
Login
User
 ↓
Email + Password
 ↓
Find User
 ↓
Compare Password
 ↓
Generate JWT
 ↓
Send Token
2. Install Required Packages
Inside your Node.js project:
npm install express mongoose bcrypt jsonwebtoken dotenv
3. User Schema
Create a model such as User.js:
const mongoose = require("mongoose");

const userSchema = new mongoose.Schema({
  name: {
    type: String,
    required: true
  },

  email: {
    type: String,
    required: true,
    unique: true
  },

  password: {
    type: String,
    required: true
  }
});

module.exports = mongoose.model("User", userSchema);
4. Registration
The registration process:
Name + Email + Password
          ↓
      Hash password
          ↓
      Save in MongoDB
Example:
const bcrypt = require("bcrypt");

app.post("/register", async (req, res) => {
  try {
    const { name, email, password } = req.body;

    const existingUser = await User.findOne({ email });

    if (existingUser) {
      return res.status(409).json({
        message: "User already exists"
      });
    }

    const hashedPassword = await bcrypt.hash(password, 10);

    const user = await User.create({
      name,
      email,
      password: hashedPassword
    });

    res.status(201).json({
      message: "Registration successful",
      userId: user._id
    });

  } catch (error) {
    res.status(500).json({
      message: "Server error"
    });
  }
});
Notice that the original password isn't stored directly.
5. Login
During login, we find the user and compare the entered password with the stored hash.
const jwt = require("jsonwebtoken");

app.post("/login", async (req, res) => {
  try {
    const { email, password } = req.body;

    const user = await User.findOne({ email });

    if (!user) {
      return res.status(401).json({
        message: "Invalid email or password"
      });
    }

    const passwordMatch = await bcrypt.compare(
      password,
      user.password
    );

    if (!passwordMatch) {
      return res.status(401).json({
        message: "Invalid email or password"
      });
    }

    const token = jwt.sign(
      { userId: user._id },
      process.env.JWT_SECRET,
      { expiresIn: "1h" }
    );

    res.json({
      message: "Login successful",
      token
    });

  } catch (error) {
    res.status(500).json({
      message: "Server error"
    });
  }
});
6. .env
Create a .env file:
MONGODB_URI=mongodb://127.0.0.1:27017/collegeDB
JWT_SECRET=replace-with-a-long-random-secret
PORT=3000
Load it:
require("dotenv").config();
For a real application, keep secrets out of source control and don't publish your .env file.
7. Protected Route
After login, the client can send the JWT when requesting protected resources.
A common format is:
Authorization: Bearer YOUR_TOKEN
Middleware:
function authenticateToken(req, res, next) {
  const authHeader = req.headers.authorization;
  const token = authHeader?.split(" ")[1];

  if (!token) {
    return res.status(401).json({
      message: "Authentication required"
    });
  }

  try {
    const user = jwt.verify(
      token,
      process.env.JWT_SECRET
    );

    req.user = user;
    next();

  } catch (error) {
    return res.status(403).json({
      message: "Invalid or expired token"
    });
  }
}
Protected route:
app.get("/profile", authenticateToken, (req, res) => {
  res.json({
    message: "Protected profile",
    userId: req.user.userId
  });
});
8. Testing in Postman
Register
POST
http://localhost:3000/register
Body → raw → JSON:
{
  "name": "Student",
  "email": "student@example.com",
  "password": "example-password"
}
Login
POST
http://localhost:3000/login
Body:
{
  "email": "student@example.com",
  "password": "example-password"
}
The response contains a JWT.
For a protected request:
GET
http://localhost:3000/profile
Header:
Authorization: Bearer YOUR_TOKEN
A JWT-based authentication system typically works by registering a user, securely hashing the password, storing the user in MongoDB, verifying credentials during login, generating a JWT, and verifying that token on protected routes.
JWT Login & Registration System
Now let's understand how a typical registration + login system works using:
Node.js + Express + MongoDB + Mongoose + bcrypt + JWT
1. Overall Flow
Registration
User
 ↓
Email + Password
 ↓
Hash Password
 ↓
MongoDB
Login
User
 ↓
Email + Password
 ↓
Find User
 ↓
Compare Password
 ↓
Generate JWT
 ↓
Send Token
2. Install Required Packages
Inside your Node.js project:
npm install express mongoose bcrypt jsonwebtoken dotenv
3. User Schema
Create a model such as User.js:
const mongoose = require("mongoose");

const userSchema = new mongoose.Schema({
  name: {
    type: String,
    required: true
  },

  email: {
    type: String,
    required: true,
    unique: true
  },

  password: {
    type: String,
    required: true
  }
});

module.exports = mongoose.model("User", userSchema);
4. Registration
The registration process:
Name + Email + Password
          ↓
      Hash password
          ↓
      Save in MongoDB
Example:
const bcrypt = require("bcrypt");

app.post("/register", async (req, res) => {
  try {
    const { name, email, password } = req.body;

    const existingUser = await User.findOne({ email });

    if (existingUser) {
      return res.status(409).json({
        message: "User already exists"
      });
    }

    const hashedPassword = await bcrypt.hash(password, 10);

    const user = await User.create({
      name,
      email,
      password: hashedPassword
    });

    res.status(201).json({
      message: "Registration successful",
      userId: user._id
    });

  } catch (error) {
    res.status(500).json({
      message: "Server error"
    });
  }
});
Notice that the original password isn't stored directly.
5. Login
During login, we find the user and compare the entered password with the stored hash.
const jwt = require("jsonwebtoken");

app.post("/login", async (req, res) => {
  try {
    const { email, password } = req.body;

    const user = await User.findOne({ email });

    if (!user) {
      return res.status(401).json({
        message: "Invalid email or password"
      });
    }

    const passwordMatch = await bcrypt.compare(
      password,
      user.password
    );

    if (!passwordMatch) {
      return res.status(401).json({
        message: "Invalid email or password"
      });
    }

    const token = jwt.sign(
      { userId: user._id },
      process.env.JWT_SECRET,
      { expiresIn: "1h" }
    );

    res.json({
      message: "Login successful",
      token
    });

  } catch (error) {
    res.status(500).json({
      message: "Server error"
    });
  }
});
6. .env
Create a .env file:
MONGODB_URI=mongodb://127.0.0.1:27017/collegeDB
JWT_SECRET=replace-with-a-long-random-secret
PORT=3000
Load it:
require("dotenv").config();
For a real application, keep secrets out of source control and don't publish your .env file.
7. Protected Route
After login, the client can send the JWT when requesting protected resources.
A common format is:
Authorization: Bearer YOUR_TOKEN
Middleware:
function authenticateToken(req, res, next) {
  const authHeader = req.headers.authorization;
  const token = authHeader?.split(" ")[1];

  if (!token) {
    return res.status(401).json({
      message: "Authentication required"
    });
  }

  try {
    const user = jwt.verify(
      token,
      process.env.JWT_SECRET
    );

    req.user = user;
    next();

  } catch (error) {
    return res.status(403).json({
      message: "Invalid or expired token"
    });
  }
}
Protected route:
app.get("/profile", authenticateToken, (req, res) => {
  res.json({
    message: "Protected profile",
    userId: req.user.userId
  });
});
8. Testing in Postman
Register
POST
http://localhost:3000/register
Body → raw → JSON:
{
  "name": "Student",
  "email": "student@example.com",
  "password": "example-password"
}
Login
POST
http://localhost:3000/login
Body:
{
  "email": "student@example.com",
  "password": "example-password"
}
The response contains a JWT.
For a protected request:
GET
http://localhost:3000/profile
Header:
Authorization: Bearer YOUR_TOKEN
A JWT-based authentication system typically works by registering a user, securely hashing the password, storing the user in MongoDB, verifying credentials during login, generating a JWT, and verifying that token on protected routes.
