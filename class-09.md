# Forms and JS Events


## Forms

[Main Page](https://jrdelmu.github.io/reading-notes/)

- An example of how a form works is the google home page where the information is input into the bar and a button is pressed to trigger a google search.
- various forms of information mation can be input in forms. So in order to differentiate from all that data, information is sent using name and value pairs.
  - `userid = tryndamere`
  - the 'userid' is the name and 'tryndamere' is the value
- forms are housed with the `<form>` element.
- Types of forms:
  - text input
    - ex. `<input type = "text" name = "username"> size = "10" maxlength = "25" />`
  - password input
  - text area
  - radio button
  - checkbox 
  - drop down list
  - multiple select box

## Events
-  A specific instance of an event occuring is when a user inputs his data into their social media account. When they click the Sign in button they are triggering and event that activates a function or a script.
- steps to trigger an event
- three ways to bind an event to an element
 - HTML event handlers
   - usually found in older code, bad practice
 - traditional DOM event handlers
   - `element.onevent = functionName`
   - element = element, oneevent = event, and functionName = code
 - DOM level 2 event listeners 
 - Event listeners can use more than function at a time. Not supported by older browsers.
  - `element.addEventListener('event', functionName, [Boolean])`
- **Event Bubbling** flows outwards:
  - `<a> --> <li> --> <ul> --> <body> --> <html> --> <document> `
- **Event capturing** flows inwards:
  - `<document> <-- <html> <-- <body> <-- <ul> <-- <li> <-- <a>`