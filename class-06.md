# Problem Domain, Objects, and the DOM

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Object Literals

**Objects** are a collection of properties. Properties consist of a key-value pair.

```
const exerciseData = {
  totalSteps(**key name**): 5435(**value**),
  totalMiles: 4323,
  avgCalorieBurn: 345345
  workoutsThisWeek: ‘5 of 7’
  avgGoodSleep: ‘3:12’
};
```
Objects can be accessed using something called the **dot notation**.

`exerciseData.totalMiles`

An object can be updated.

Object:
`const userYelpRating = {}`

`userYelpRating['username']` = 5 OR `userYelpRating.username = 5`

## Document Object Model

The document object model (DOM) allows a developer to update and modify the contents of a webpage in browser window form. Methods used for finding elements in a DOM tree are called **DOM queries**.

- `getElementById()`: quickest and most efficient way to access an element
- `querySelector()`: can be used to target more elements because its parameter is a CSS selector
- `item()` method: returns an invdividual node from the node list
