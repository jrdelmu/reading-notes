# Introductory HTML and JavaScript 

## Structure

HTML is the **structure** behind a webpage. Before CSS and JavaScript can be utilized a foundation must be laid out beforehand and HTML provides just that. Similar to a news paper or a word document, HTML allows the developer to create headings, subheadings and personalize the layout of the content in order to help the audience better understand and navigate through it.

**Elements** communicate to the browser what kind of information will be inserted inbetween the opening(`<p>`) and closing tags (`</p>`). 

**Elements:**
- `<html>` indicates that anything with the opening and closing tag is HTML code.
- `<body>` content that will be shown in the main browser.
- `<h1>` This element is the top level header and every header after is a subheading (`<h2>`, `<h3>`, and etc.)
- `<p>` This element will usually contain core content.

## Extra Markup

### Different Versions of HTML

- **HTML 4**
    - Included appearance elements that are no longer recommended for use such as `<center>`, `<font>`, and etc.
- **XHTML 1.0**
    - A reformulated version of HTML 4 that follows XML rules. Created to make new markup languages.
- **HTML 5**
    - The current iteration of HTML, includes changes such as new elements and not needing to close all tags.

### Comments
`<!-- content here -->`  
Will add a comment to code. Comments can be useful in ways like having another developer understand your thought process while writing the code.

### ID Attribute

`<p id='content here'>`  
The ID will allow the developer to specifically identify elements. Useful in cases like CSS, when a developer would want to make appearance changes to one paragraph rather than all of them.

### Class Attribute
`<p class = 'content here'>`  
Similar to ID but allows the developer to identify many elements instead of just one.

### Block and Inline Elements

Block elements such as `<h1>`, `<p>`, `<ul>`, and `<li>` will only take up as much space as there is content while Inline elements such as `<a>`, `<b>`, `<em>`, and `<img>` will take up a whole row of the page regardless of the length of the content. 

### div and span  

`<div>` will allow developers to group block level elements together hiwle `<span>` will group inline level elements together.

## HTML5 Layout

Prior to HTML 5 `<div>` elements were primarily used to group related content together. Now instead of using div to handle all forms of content like articles and footers new elements have been created instead.

- OLD: `<div id = 'footer'>`
- NEW: `<footer>`

Examples: 

- `<header>`
- `<footer>`
- `<nav>`
- `<article>`
- `<aside>`
- `<section>`
- `<hgroup>`
- `<figure>`

For the most parts these elements are self explanitory and operate similar to a `<div>` but will help to better identify the kind of content that will be inside the elements. For example the `<header>` and `<footer>` are going to contain things such the site name and copywrite information. Another one is `<nav>`, this element could contain navigational links for the main page of the website.

## Process & Design

It important to keep in mind the target audience for anyone website being created. This is crucial because it will directly impact things such as the content and ergonomics of the site. 

Things to keep in mind when building a site:

- Who is it for?
- Why are they visiting?
- What are they trying to do on your site?
- What kind of information are they looking for?
- How often will it be visited?

## The ABC of Programming

A **script** is a set of instructions that a computer follows in order to achieve its goal. In order to write a script a goal must be set. Once that is done the developer can start designing the script. Then finally each step can be coded out. It is important to understand the vocabulary the computer uses in order to create **syntax**. 

### Objects & Properties 

To a computer an **Object** is considered a *thing*. An object can contain things such as **properties**, **events** and **methods**. **Properties** are considered the *characteristics* of the object. The properties contain a name and value that reveal information about the object.

### Events  

An example of an **event** is a user interacting with a website. For example, the event of a user making a window smaller will trigger the website to resize and restructure itself to fit properly into the window still.

### Methods

**Methods** are set ways in which people can interact with objects.

Example:

`console.log('hello world)`

**Console** is and object that provides access to the browser. **Log** is the method that is being used to write "hello world to the console".