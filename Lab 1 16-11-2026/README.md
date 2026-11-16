## Objectives

- To get introduced to the course CSE 3154: Web Programming.
- To understand the course structure (3 contact hours per week, 1.50 credits).
- To learn about the major topics that will be covered during the course.
- To become familiar with the basic web technologies: HTML, CSS, and JavaScript.

## Theory

Web programming is the process of designing and building applications that run on the internet or an intranet. A web application works on a client-server model. The browser (client) sends a request, and the web server processes it and sends back a response. Client-side technologies include HTML, CSS, DHTML, and JavaScript, whereas server-side technologies include PHP and Servlets.

A web server is software that receives and answers requests from browsers. Packages such as XAMPP bundle a web server (Apache), a database (MySQL), and PHP into one installation, so a developer can build and test web applications on a local computer. IIS is another web server, developed by Microsoft.

### HyperText Markup Language (HTML)

HTML is the standard markup language used to create the structure and content of a web page. It uses elements written inside tags, such as the heading tag h1, the paragraph tag p, and the anchor tag a, to define headings, paragraphs, links, images, and forms.

### Cascading Style Sheets (CSS)

CSS is a style sheet language used to control the appearance of a web page. It defines colors, fonts, spacing, and layout, and it separates the design of a page from its content.

### JavaScript

JavaScript is a scripting language used to make a web page interactive. It handles events such as button clicks, validates user input in forms, and changes the content of a page without reloading it.

In summary, HTML builds the structure of a page, CSS styles it, and JavaScript adds behavior to it. A simple example that uses all three is shown below.

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 { color: blue; }
  </style>
</head>
<body>
  <h1>Hello, Web!</h1>
  <button onclick="alert('Welcome to CSE 3154')">Click Me</button>
</body>
</html>
```

## Discussion

In the first class, the instructor introduced the course contents, which include IIS and XAMPP (bundle server), validation, built-in objects and event handling, DHTML with JavaScript, Servlets, database connectivity, programming in a web environment and the anatomy of a PHP page, PHP advanced concepts, creating and using forms, XML, AJAX, and Web Services.

The instructor also wrote the basic HTML, CSS, and JavaScript concepts on the board to explain how these three technologies work together in a web page. The course is theory plus practical in nature, so regular lab practice is required. Lab work will be submitted through a GitHub repository named with the student's roll number and course code (2304027_CSE_3154), instead of PDF files. Each lab will be placed in its own folder inside this repository.

## Conclusion

This introductory lab gave a clear overview of the Web Programming course and its basic technologies. Understanding the client-server model and the roles of HTML, CSS, and JavaScript will help in learning both front-end and back-end development in the coming labs. The GitHub repository has been created to submit all lab reports throughout the course.
