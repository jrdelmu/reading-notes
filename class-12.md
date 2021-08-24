# Chart.js, Canvas

[Main Page](https://jrdelmu.github.io/reading-notes/)

- Creating a line chart
`new Chart(x).Line(x);`

- Creating a pie chart
`new Chart(x).Pie(x);`

- Creating a bar chart
`new Chart(x).Bar(x);`

- The HTML element `<canvas>` is used to draw various shapes and graphics 
  - When width and height are not specified it will default to 300 px wide and 150 px height
  - `<canvas >` only supports the primitive shapes rectangles and paths
    - Paths are lists of points connected by lines that can be different shapes and colors
      - beginPath()
      - closePath()
      - stroke()
      - fill()
  - Colors and styles can be applied through JavaScript with:
   - `fillStyle`
   - `strokeStyle`
