---
title: "Tech"
date: 09/27/2023
author: "Miles Wallace"
description: ["Nav Bar", "HTML", "CSS", "Javascript",  ]
---
## "Nav Bar HTML, CSS and Javascript"
#### _09/27/2023_ 
____
I'll show you step by step a guide to a Navbar setup for HTML, CSS and Javascript.  
To set up an HTML and CSS with JavaScript code that highlights the active page link in your navigation based on the activePage variable and the navLinks query selector, you can follow these steps:  

1. Create an HTML file (e.g., index.html) for your web page:
<!-- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Website Title</title>
</head>
<body>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <script src="script.js"></script>
</body>
</html> 
-->

2. Create a CSS file (e.g., styles.css) to style your navigation and highlight the active link:  

nav ul {
    list-style-type: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #333;
}

nav a.active {
    font-weight: bold;
    color: #007bff; /* Change the color as desired */
}

3. Create a JavaScript file (e.g., script.js) to handle the highlighting of the active link:  

// script.js

const activePage = window.location.pathname;
const navLinks = document.querySelectorAll('nav a');

navLinks.forEach(link => {
    if (link.getAttribute('href') === activePage) {
        link.classList.add('active');
    }
});  

In this setup:  

The HTML file defines a simple navigation menu with anchor links.
The CSS file styles the navigation links and adds a class (active) to style the active link differently.
The JavaScript file checks each link's href attribute against the activePage variable (which represents the current page's pathname). If they match, it adds the active class to the link, which applies the defined styling.
Make sure to place all three files (index.html, styles.css, and script.js) in the same directory for this setup to work properly.
