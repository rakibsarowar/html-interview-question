<h1> HTML5 interview questions and answers in 2021 </h1> 

🔹 1. What is an iframe and how it works?
Answer:
An iframe is an HTML document which can be embedded inside another HTML page.

Example:
<iframe src="https://github.com" height="300px" width="300px"></iframe>
<hr>

🔹 2. What is the purpose of the alt attribute on images?
Answer:
The alt attribute provides alternative information for an image if a user cannot view it. The alt attribute should be used to describe any images except those which only serve a decorative purposes, in which case it should be left empty. <hr>

🔹 3. What is the difference between span and div?
Answer:
div is a block element
span is inline element
For bonus points, you could point out that it’s illegal to place a block element inside an inline element, and that while div can have a p tag, and a p tag can have a span, it is not possible for span to have a div or p tag inside. <hr>

🔹 4. How can you highlight text in HTML?
Answer:
If you are working with an HTML5 page, the <mark> tag can be a quick and easy way of highlighting or marking text on a page:

<mark>highlighted text</mark>
To highlight text with just HTML code and support for all browsers, set the background-color style, as shown in the example below, using the HTML tag.

<span style="background-color: #FFFF00">Yellow text.</span>
<hr>

 🔹 5. What is Character Encoding?
Answer:
To display an HTML page correctly, a web browser must know which character set (character encoding) to use. This is specified in the tag:

HTML5:
<meta charset="UTF-8"> <hr>

🔹 6. What is a self closing tag?
Answer:
In HTML5 it is not strictly necessary to close certain HTML tags. The tags that aren’t required to have specific closing tags are called “self closing” tags.

An example of a self closing tag is something like a line break (<br />) or the meta tag (<meta>). This means that the following are both acceptable:

<meta charset="UTF-8">
...
<meta charset="UTF-8" /> <hr>

 🔹 07. How Can I Get Indexed Better by Search Engines?
Answer:
It is possible to get indexed better by placing the following two statements in the <HEAD> part of your documents:

<META NAME="keywords" CONTENT="keyword keyword keyword keyword">
<META NAME="description" CONTENT="description of your site">
Both may contain up to 1022 characters. If a keyword is used more than 7 times, the keywords tag will be ignored altogether. Also, you cannot put markup (other than entities) in the description or keywords list.
 
 🔹 08. Briefly describe the correct usage of the following HTML5 semantic elements: header, article, section, footer
Answer:
<header> is used to contain introductory and navigational information about a section of the page. This can include the section heading, the author’s name, time and date of publication, table of contents, or other navigational information.

<article> is meant to house a self-contained composition that can logically be independently recreated outside of the page without losing it’s meaining. Individual blog posts or news stories are good examples.

<section> is a flexible container for holding content that shares a common informational theme or purpose.

<footer> is used to hold information that should appear at the end of a section of content and contain additional information about the section. Author’s name, copyright information, and related links are typical examples of such content.
 
 
 🔹 08. What's the difference between an "attribute" and a "property" in HTML?
Answer:
Attributes are defined on the HTML markup but properties are defined on the DOM. To illustrate the difference, imagine we have this text field in our HTML: <input type="text" value="Hello">.

const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello
But after you change the value of the text field by adding "World!" to it, this becomes:

console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello World!
 <hr>
 
 🔹 09. What does a DOCTYPE do?
Answer:
DOCTYPE is an abbreviation for “document type”. It is a declaration used in HTML to distinguish between standards mode and quirks mode. Its presence tells the browser to render the web page in standards mode.

Moral of the story - just add <!DOCTYPE html> at the start of your page.
 <hr>
 
 
