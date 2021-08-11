# HTML Lists, Control Flow with JS, and the CSS Box Model

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Lists

- **ordered lists**
  - A numbered list. 
  - The `<ol>` element is used to create an ordered list and `<li>` is used to list the items on the list.
- **unordered lists**
  - A bullet point list.
  - The `<ul>` element is used to create an ordered list and `<li>` is used in the same way as `<ol>` above.
- **definition lists**
  - A list where a term is designated then defined.
  - The `<dl>` element is used to create the list, `<dt>` will list the term, and `<dd>` will define the term.
- **nested lists**
  - A list within a list.

example of an **unordered list**:

`<ul>`
`    <li>Item 1</li>`
`    <li>Item 2</li>`
`    <li>Item 3</li>`
`</ul>`

example of an **definition list**:

`<dl>`
`    <dt>Term 1</dt>`
`    <dd>Definition 1</dd>`
`    <dt>Term 2</dt>`
`    <dd>Definition 2</dd>`
`    <dt>Term 3</dt>`
`    <dd>Definition 3</dd>`
`</dl>`

## Boxes

### Box Dimensions

In CSS box dimension can be controlled with **width** and **height**.

CSS:

`body {`
`  height: 10px;`
`  width: 10px;`
`}`

### Limiting Width

Contents of a page can be limited  or maxed using **min-width** and **max-width**.

`div {`
`  min-width: 200px;`
`  max-width: 500px;`
`}`

### Limiting Height

Liminiting height functions in the same way as liminiting with by using **min-height** and **max-height**

### Overflow content

The overflow property will either tell the browser to hide or add a scroll bar to content that cannot be contained within its box. 

`p{`
`  overflow: hidden;`
`}`

`p{`
`  overflow: scroll;`
`}`

### Border, Margin, Padding

- A **border** is the border around an element. The border can be modified in size, style and color.

- **Padding** is the space between the content and the border of an element. Just like border, padding can be modified in size as well.

- **Margin** is the space outside of an elements border and just like the two above, can be modified in size.

## Basic JavaScript Instructions

### Arrays

An **array** is a datastructure in which multiple values can be stored. An array can be named and declared like any variable but the values will be placed in square brackets.

`Let favAnimal = ['cat', 'dog', 'bird']`

Each value is assigned an **index** starting at 0. So cat would be 0, dog would be 1, bird would be 2 and so on. To choose a specific value you would utilize the index.

`console.log(favAnimal(1));`

The above would call upon dog because it is located in index 1.

### Loops

Loops Allow us to repeat code.

Loop Types:

- for loop
- while loop
- for...of loop
- for...in loop

`let loop = function () {`
`  for(let i = 0; i < 10; i++){`
`    console.log('loops')`
`  }`
`}`

`loop(1)`

The function above will print the word 'loop' ten times.