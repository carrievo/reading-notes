# Docs for the HTML <canvas> Element & Chart.js

- chart.js is a chart library and displays the chart on an HTML canvas element. 
- You need to start with ```<script>``` and then..
```<canvas id="tutorial" width="150" height="150"></canvas>```

- JS comes with built-in chart types:
  1. line
  2. bar
  3. radar
  4. doughnut and pie
  5. polar area
  6. buble
  7. scatter

- Paths: Lines that create shapes with various widths and colors.
  - To create a path:
    1. Establish a path.
    2. Use Methods to draw the path.
    3. fill using one of the fill or strok functions.
  - beginPath() - establishes the new path.
  - closePath() - line from the start to the current line or path.
  - stroke() - creates an outline of a shape.
  - fill() - filles the area to render a shape.

- Color Methods
  - fillstyle = "color" 
    - fill in the shape you want with color.
  - strokeStyle = "color" 
    - adds outline shape with color.


*Referenced*
- https://www.chartjs.org/docs/latest/
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text
