# Basics of HTML, CSS & JS assignment 

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Text

### Headings

There are six levels of headings in HTML. `<h1>` being the highest level and `<h6>` being the lowest level. `<h1>` will typically be considered the primary header while the others are subheaders.  

### Paragraphs

`<p>` is both a place to put content, such as paragraphs or any other relevant information pertaining to the topic, as well as splitting it up into sections, similar to a `<div>`.

### Bold & Italic

The `<b>` tag will **bolden** a words while `<i>` will *italicize* words.

### Superscript & Subscript

`<sup>` will raise a number in the same manner as E=MC^**2** while `<sub>` will do the exact opposite by lowering the number in the same manner as a foot note.

### Line Breaks & Horizontal Rules

- `<br>` functions as a line break.
- `<hr />` will create a horizontal line/border

### Semantic Markup

Semantic markup will help indicate what kind of information is going to be displayed.

Examples:
- `<strong>`: Indicates importance while adding a bold effect to text. 
- `<em>`: Indicates emphasis while also italicizing text. 
- `<blockquote>`
- `<q>`
- `<abbr>`
- `<dfn>`
- `<address>`
- `<ins>`
- `<del>`
- `<s>`

## Introducing CSS

HTML can be styled with CSS using the elements within an HTML file.

`h2 {`
  `background-color: pink;`
`}`

- **selector:** h2
- **declaration:** background-color: pink
- **properties:** background-color:
- **value:** pink

The **selector** selects which elements that the changes will be applied to. The **property** indicates what kind of change you want to make to the element, and in this case its the background color of the element h2. **Value** will be used to specify the kind of change you will make to the element, such as color, size and etc.

### Internal and external CSS

CSS can be applied externally with `<link>` and internally with `<style>`.

## Basic JavaScript Instructions

### Variables

**Variables** allow us to store values and give the value a name so that we can refer back to it later.

Example:

`var favDino = 'T. Rex'`

The variable 'favDino' is declared using the keyword 'var' and the value is set to 'T. Rex'. A variable can also be declared with **const** and **let**.

### Datatypes

Javascript consist of three different datatypes:

- Numeric: numbers
- String: letters
- Boolean: True or False

### Arrays

An **array** is a datastructure in which multiple values can be stored. An array can be named and declared like any variable but the values will be placed in square brackets.

`Let favAnimal = ['cat', 'dog', 'bird']`

Each value is assigned an **index** starting at 0. So cat would be 0, dog would be 1, bird would be 2 and so on. To choose a specific value you would utilize the index.

`console.log(favAnimal(1));`

The above would call upon dog because it is located in index 1.

### Decisions and Loops

Decisions can be made utilizing **If statements**.

`let catDog = 'dog'`
`if(catDog === 'dog'){`
`  console.log('good choice')`
`} else {`
`  console.log('sorry, try again')`
`}`

### Comparison Operators:

- `==` is equal to
- `!=` is not equal to
- `===` strict equal to
- `!==` strict not equal to
- `>` greater than
- `<`less than
- `>=` greater than or equal to
- `<=` less than or equal to

### Logical Operators

- `&&` logical and
- `||` logical or
- `!` logical no