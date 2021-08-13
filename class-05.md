# Images, Color, Text

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Images

Images can be applied with the `<img>` element.

`<img src = "insert website here" alt="insert image title/description here" width="200" height="200" align="left"/>`

- The ***src*** is responsible for telling the browser where to find the image.
- Should there be an error with the picture for whatever reason, the **alt** will display text instead.
- The **height** and **width** can also be set and adjusted within the img element.
- Images can be moved using **align** and can be placed in either the top, middle, bottom, left or right side of the page.

## Color

Colors can be applied in three different ways:

- **color name**
    - red, blue, green and etc.
- **RGB**
    - `color:rgb(255,0,0)` is equal to the color red
- **hex codes**
    - `color: #ff0000` is equal to the color red 

## Text

```
p {
  font-family: times, times new roman, serif;
  font-size: 10px;
}

- There are many styles of text to choose from.
  - serif
    - georgia
    - times
    - times new roman
  - sans-serif
    - arial
    - verdana
    - helvetica
  - monospace
    - courier
    - courier new
- The styles can be applied with wfont-family as seen above.
- Size can also be altered using font-size.
  - sizes can be applied with these units:
    - pixels
    - percentages
    - ems