This Readme file is for Sathwik Reddy Portfolio. 

All tags used : 

<!DOCTYPE html>:
This declaration specifies that the document is an HTML5 document.

<html lang="en">:
The opening <html> tag defines the beginning of the HTML document.
The lang attribute specifies the language of the document, which is set to English in this case.

<head> ... </head>:
The <head> section contains metadata and links to external resources, such as stylesheets and fonts.

<meta charset="UTF-8">:
This <meta> tag specifies the character encoding for the document, which is UTF-8, a widely used character encoding for handling various characters and symbols.

<meta name="viewport" content="width=device-width, initial-scale=1.0">:
This <meta> tag sets the viewport properties for responsive design, ensuring that the webpage adapts to different device screen sizes.

<link rel="stylesheet" href="styles.css">:
This <link> tag links an external CSS stylesheet named "styles.css" to apply styling to the webpage.

<title>Sathwik Reddy Portfolio</title>:
The <title> tag sets the title of the webpage, which is displayed in the browser's title bar or tab.

<link rel="icon" type="image/x-icon" href="/images/favicon.png">:
This <link> tag specifies the favicon (the small icon displayed in the browser tab) for the webpage.

<header> ... </header>:
The <header> tag defines the header section of the webpage, typically containing a site logo, name, and navigation links.

<a> (Anchor) Tags:
These <a> tags represent navigation links within the header section. They use the href attribute to link to specific sections of the webpage using anchor IDs.

<div class="column"> tag: 
used to create individual columns 

<section> Tags:
<section id="About">, <section id="Experience">, and others: These <section> tags define different sections of the webpage with unique IDs. Each section typically contains content related to a specific topic.

<p> Tags:
<p> tags are used to enclose paragraphs of text within the sections. They represent paragraphs of content.

<img> Tags:
<img> tags are used to display images on the webpage, such as the logo and certificate images.
They include attributes like src (source) to specify the image file and alt to provide alternative text for accessibility.

<table> and <tr> Tags:
<table> tags are used to create tables for organizing content.
<tr> tags represent table rows within the table structure.
<td> Tags:
<td> tags define table cells within rows to hold content or images.

<figcaption> Tag:
<figcaption> tags are used within <td> elements to provide captions for images.

<a> (Anchor) Tags (Footer):
In the footer section, <a> tags are used to create links to social media profiles and contact information.

<audio> and <video> Tags:
<audio> and <video> tags are used to embed audio and video content, respectively, on the webpage.
They include attributes like controls to provide play/pause controls and source to specify the media file.
These tags collectively structure and define the content and styling of the portfolio website. Each tag serves a specific purpose in organizing and presenting information to the user.

<form action="mailto:/Tel:" method="POST">:
The <form> tag is used to create an HTML form that allows users to submit information.
The action attribute specifies the email address where the form data will be sent when submitted (in this case, "youremail@example.com").
The method attribute specifies the HTTP method to be used when submitting the form, which is "POST" in this case.

CSS:
"styles.css" provided enables styling of the HTML elements in index.html and feedback.html 

tags: <body> <h2> <header><form><label><input><textarea><button><p><a><section><table><tr><td><th><img><summary>
tags: <audio><footer>
classes: .sidebar .sidebar a .sidebar a.active .sidebar a:hover:not(.active) .certificateimg 
classes: .Northeastern .SRMAP .skills .Cognizant .column .row .msg
ID: #About, #favi

Position : we used position two times. firstly, we set the value of position to 'absolute' and it is applied to the .sidebar element.
secondly, When the screen width is less than 2000px in @media screen, the sidebar is set to a 'relative' position, which means it will be positioned relative to its normal position within the document flow. 

media queries: 
 there are two media queries used to apply different styles based on the screen width. Media queries are used to make websites responsive and adapt their layout and styling to different screen sizes and devices. 
@media screen and (max-width: px)

float: property is used to control the horizontal alignment of elements within the "Experience" section

overflow: is used to control what happens when the content within a specific element overflows its designated space. 
overflow property is applied to the .sidebar class.









