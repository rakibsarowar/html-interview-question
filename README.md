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
<meta charset="UTF-8" />

