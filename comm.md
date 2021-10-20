<!--HTML is the standard markup language for creating Web pages.-->

<!-- A markup language is a computer language for clarifying the contents of a document. It was designed to process, define, and present computer text in a form that humans can read. It specifies the code used to format text, including the style and layout the programmer wants the document to appear. It uses tags to define these elements.-->

<!-- SOME PROPERTIES OF HTML -->

<!--
*HTML stands for Hyper Text Markup Language
*HTML is the standard markup language for creating Web pages
*HTML describes the structure of a Web page
*HTML consists of a series of elements
*HTML elements tell the browser how to display the content
*HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
-->

<!--A SIMPLE HTML DOCUMENT BELOW-->

<!--GIVEN IN THE index.html file -->

<!--EXPLAINING THE ABOVE CODE-->

<!--
*The <!DOCTYPE html> declaration defines that this document is an HTML5 document
*The <html> element is the root element of an HTML page
*The <head> element contains meta information about the HTML page
*(META DATA specifies additional information about a document in a variety of ways. The <meta> tag is used to provide such additional information. The most important thing about meta tags is that we can include one or more meta tags in our document based on what information we want to keep in our document but in general, meta tags do not impact physical appearance of the document so from appearance point of view, it does not matter if we include them or not.)
*The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
*The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
*The <h1> element defines a large heading
*The <p> element defines a paragraph
    
-->

<!--HTML ELEMENTS-->

<!--An HTML element is defined by a start tag, some content, and an end tag:

<tagname>Content goes here...</tagname>

So basically it's (HTML ELEMENT) is  everything from the start tag to the end tag

Examples 

<h1>My First Heading</h1>

<p>My first paragraph.</p>

Start tag	Element content	End tag

<h1>	My First Heading	</h1>

<p>	My first paragraph.	</p>

<br>	none	none  (THIS IS AN EMPTY ELEMENT AS IT DOES NOT HAVE ANY CONTENT AND NO END TAG)

-->

<!--WEB BROWSER -->

<!--The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document -->

<!--
2021-10-19-08-17-28.png

In this picture we can see the overall layout of the HTML document 

The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab.

-->

<!--BASICS OF HTML EXPLAINED THROUGH EXAMPLES-->

<!--HTML DOCUMENTS-->

<!--
All HTML documents must start with a document type declaration: <!DOCTYPE html>.

The HTML document itself begins with <html> and ends with </html>.

The visible part of the HTML document is between <body> and </body>

-->

<!--The <!DOCTYPE> Declaration-->

<!--

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The <!DOCTYPE> declaration is not case sensitive.

The <!DOCTYPE> declaration for HTML5 is 

<!DOCTYPE html>

    
-->

<!--HTML HEADINGS-->

<!--
HTML headings are defined with the <h1> to <h6> tags.

<h1> defines the most important heading. <h6> defines the least important heading.

Example

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>

-->

<!--HTML PARAGRAPHS-->

<!-- 

HTML paragraphs are defined with the <p> tag

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

-->

<!--HTML LINKS -->

<!--

HTML links are defined with the <a> tag

<a href="https://www.tottenhamhotspur.com/">TOTTENHAM</a>

Some important points :-

The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.

-->

<!--HTML IMAGES-->

<!--
HTML images are defined with the <img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes.

<img src="https://everythingbarca.com/wp-content/uploads/getty-images/2017/07/1231862540.jpeg" alt="HARRY KANEEEEEEEEEEE" width="104" height="142">

    

-->

<!--HTML ELEMENTS IN DETAILS -->

<!--
We discussed about html elements above . lets get more specific 

As discussed above, 

An HTML element is defined by a start tag, some content, and an end tag.

The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>

Examples :-

<h1>My First Heading</h1>
<p>My first paragraph.</p>

Empty Elements - 

Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

-->

<!--NESTED HTML ELEMENTS-->

<!--

HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

In the code above we created

we see that  

The <html> element is the root element and it defines the whole HTML document.

It has a start tag <html> and an end tag </html>.

Then, inside the <html> element there is a <head> amd <body> element

#Code given below

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>THIS IS A SIMPLE HTML DOCUMENT</title>
  </head>

  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>

Here the html element there is a <head> and <body> elements where the <head> contains <meta> elements and <title> element. 

#Code given below

<meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>THIS IS A SIMPLE HTML DOCUMENT</title>

Then comes <body>

The <body> element defines the document's body.

It has a start tag <body> and an end tag </body>.

Then, inside the <body> element there are two other elements: <h1> and <p>

#Code given below

<h1>My First Heading</h1>
<p>My first paragraph.</p>

The <h1> element defines a heading.

It has a start tag <h1> and an end tag </h1>

The <p> element defines a paragraph.

It has a start tag <p> and an end tag </p>
-->

<!--WE SHOULD NEVER SKIP THE END TAG UNLESS ITS AN EMPTY ELEMENTS-->

<!--EMPTY HTML ELEMENTS-->

<!--

HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag

<p>This is a <br> paragraph with a line break.</p>

 
-->

<!--HTML IS NOT CASE SENSITIVE-->

<!--

HTML tags are not case sensitive: <P> means the same as <p>.
    
-->

<!--HTML ATTRIBUTES-->

<!--

 HTML attributes provide additional information about HTML elements

*All HTML elements can have attributes
*Attributes provide additional information about elements
*Attributes are always specified in the start tag
*Attributes usually come in name/value pairs like: name="value"

FOR EXAMPLES

The href Attribute :-

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to

<a href="https://www.tottenhamhotspur.com/">TOTTENHAM</a>

The src Attribute :-
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed

<img src="https://everythingbarca.com/wp-content/uploads/getty-images/2017/07/1231862540.jpeg">

There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://everythingbarca.com/wp-content/uploads/getty-images/2017/07/1231862540.jpeg".

Notes: External images might be under copyright. If we do not get permission to use it, we may be in violation of copyright laws. In addition, we cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="harry_kane.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/harry_kane.jpg".

Tip: It is almost always best to use relative URLs. They will not break if we change domain.
    
-->

<!--The width and height Attributes-->

<!--

The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels)

<img src="2021-10-19-08-17-28.png" width="500" height="600">
 -->

<!--The alt Attribute-->

<!--
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader

<img src="2021-10-19-08-17-28.png" alt="HTML VISUALIZATION">
-->

<!--The style Attribute-->

<!--

The style attribute is used to add styles to an element, such as color, font, size, and more.

<p style="color:red;">This is a red paragraph.</p>

though its not recommended to use as it can be used with CSS
-->

<!--THE lang Attribute-->

<!--
WE should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

-->

<!--The title Attribute-->

<!--The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element

<p title="I'm a tooltip">This is a paragraph.</p>

-->

<!--We Suggest: Always Use Lowercase Attributes-->

<!--
The HTML standard does not require lowercase attribute names.

The title attribute (and all other attributes) can be written with uppercase or lowercase like title or TITLE.

-->

<!--We Suggest: Always Quote Attribute Values-->

<!--
The HTML standard does not require quotes around attribute values.

However, we should use  quotes in HTML

-->

<!--Single or Double Quotes?-->

<!--
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes

-->
