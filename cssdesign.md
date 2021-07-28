# Design web pages with CSS assignment

[Main Page](https://jrdelmu.github.io/reading-notes/)

## CSS (Cascading Style Sheets)
CSS is a language that will allow for much more precise fine tuning in regards to the styling, structure, and ergonomics of a webpage.

## How to add CSS

CSS can be implmented in three different ways:

- **External:** by linking an HTML sheet to your external CSS sheet
    - `<link rel="stylesheet" href="NAME OF STYLE SHEET HERE">`
- **Internal:** incorporating `<style>` tags directly into your HTML sheet
- **Inline:** a form of interal styling but only applied to a specific line within the HTML sheet
    - `<p style="color:red;">INSERT TEXT HERE</p>`

## Syntax Format

h1 {  
      color: navy;  
    }  
      
The code above is the basic syntax layout for CSS. The **h1** is the selector that allows us to specify what we want to style on the HTML sheet. Inside of the curly braces are declarations. Declarations take the form of **property** and **value**. Color is the property and navy is the value followed a semicolon.

## Color

Colors can be selected in three different ways:

- color name
    - red, blue, green and etc.
- RGB 
    - `color:rgb(255,0,0)` is equal to the color red
- hexidecimal
    - `color: #ff0000` is equal to the color red 