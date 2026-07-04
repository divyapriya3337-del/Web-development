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
    <td>Gyan Kishore</td>
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
Gyan Kishore
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
