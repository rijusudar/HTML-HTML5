# HTML/HTML 5 What & How!

  
HTML - HPERTEXT MARK UP LANGUAGE

 - HTML is a mark up language
 - It made of elements formed by tags.
 - It is defined by a specification maintained by W3C.

# HTML Structure

    <!DOCTYPE html>
    <html>
		<head>
			<meta  charset="utf-8">
			<meta  http-equiv="X-UA-Compatible"  content="IE=edge">
			<title>Page Title</title>
			<meta  name="description"  content="Page desscription">
			<meta  name="viewport"  content="width=device-width, initial-scale=1">
			<link  rel="stylesheet"  href="style.css">
		</head>
	    <body>

			<h1>My First Heading</h1>
			<p>My first paragraph.</p>
			
			<script  src=""  async  defer></script>
	    </body>
    </html>



## !Doctype html 

 - Ensure that the browser renders the page in **Standards mode**
 - Without the  `DOCTYPE`  you are forcing the browsers to render in  [Quirks Mode](http://en.wikipedia.org/wiki/Quirks_mode). [Demo](http://jkorpela.fi/quirks-mode.html#demo)

# What is HTML5

-   Encouraging semantic (meaningful) markup
-   Separating design from content
-   Promoting accessibility and design responsiveness
-   Reducing the overlap between HTML, CSS, and JavaScript
-   Supporting rich media experiences while eliminating the need for plugins such as Flash or Java


## Encouraging semantic (meaningful) markup

-   `<header>`
-   `<nav>`
-   `<main>`
-   `<article>`
-   `<aside>`
-   `<section>`
-   `<footer>`

&& 
New text-level (inline) elements have also been introduced, such as `<address>`and `<time>`
  

## Separating design from content

HTML5 specification strongly  **discourages**  non-meaningful markup — markup intended only to tell the browser how to display things. This includes things like:

-   declaring fonts and text colors
-   setting text alignment or justification
-   placing borders on tables
-   defining how text wraps around images


## Promoting accessibility and design responsiveness

Not everyone interacts with the web the same way you do.

 - “Conventional” devices — desktops, laptops, tablets, and phones — present a wide range of screen sizes, screen aspect ratios, display resolutions, and user interaction experiences.
 - Blind and visually impaired persons browse the web also, and they use a variety of assistive technologies to do so.  
  

## Reducing the overlap between HTML, CSS, and JavaScript

-   HTML — Content
-   CSS — Design
-   JS — Interactivity

`<img align="right" />`

## Supporting Rich Media Experiences While Eliminating the Need for Plugins Such as Flash or Java  
  
HTML5 provides support for media with elements like `<video>`and [`<audio>`], while [`<canvas>`] provides a defined space for JavaScript-created drawing and graphics.



# Why Should I Use HTML5?
-   Easier to write
-   Easier to maintain
-   Easier to redesign
-   Better for Search Engine Optimization
-   Better for the blind and visually impaired
-   Better for content aggregators and feed readers
-   Better for users on mobile devices
-   Better for users on slower internet connections
-   Fewer chances of design breaks
-   Easier to add media
-   Easier to create interactive applications
-   Deprecated features will likely stop being supported at some point, breaking your page
 

## How To Use HTML5

 - Avoid Deprecated Features
 - Learn to Use the New Features
 - Get Comfortable With CSS
 - Use the HTML5  `<!DOCTYPE>`  Declaration
 - Don't Close Null Tags 
		`<img>`  - ✅
		`<br>`    - ✅
		`<hr>`    - ✅
		
		
		<img /> - ❌
		<br />  - ❌
		<hr />  - ❌


## Validate Your Pages

The W3C provides an official [Markup Validation Service](https://validator.w3.org/), which allows you to quickly check your pages against the HTML5 specification  
  
