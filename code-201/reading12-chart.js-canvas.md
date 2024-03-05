# Chart.js, Canvas 


### [JavaScript Canvas](https://www.javascripttutorial.net/web-apis/javascript-canvas/)
#### 1. What does the `<canvas>` allow a developer to acheive?
- It is an HTML5 element that allows a developer to draw 2D graphics using JavaScript.
- The `<canvas>` element requires at least two attributes that specify the size of the canvas. These would be `width` and `height`.
- A developer can access the `width` and `height` properties of the `<canvas>` element via its DOM properties.

#### 2. What is the importance of the closing `</canvas>` tag?
- The `<canvas>` tag differs from other elements such as `<img>` because the `<canvas>` element requires a closing tag ( `</canvas>` ).
- Most modern web browsers no support the `<canvas>` element.

#### 3. Explain what the `getContext()` method does.
- The `getContext()` method returns a render context object.
- The `getContext()` method takes on argument which is the type of context.
  * For example: a developer would use "2d" to get a 2D rendering context object, which is an instance of the `CanvasRenderingContext2D interface.

### [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
#### 1. What is Chart.js and how it can be brought into your project?
- It is advertised as one of the most popular JavaScript charting library applications.
- It is open-sourced and its goal is to provide sets of the most frequently used chart types, plugins, and customization options.
- Chart.js even allows developers to combine several chart types into a mixed chart (effectively blending multiple chart types into one on the same canvas)
- I'm sure we will be using this feature to track the user's actions as we build our projects. It would be nice to be able to display data to the user once they have interacted with our teams web page.

#### 2. List 3 different Chart types you can create using Chart.js.
- Area chart
- Bar chart
- Radar chart


### [Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
#### 1. What are some advantages to displaying data via a chart over a table?
- [WebDesignerDepot.com](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) states, "Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They're easier to look at and convey data quickly, but they're not always easy to create."

#### 2. How could Chart.js aid your previously created applications visually?
- With the odd-duck lab this week, it will give my web page a better user experience, I believe, by being able to display the product data once the allotted clicks have been made.


## Things I Want to Know More About
- CanvasRenderingContext2D
- [Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
- [Applying Style and Colors - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- [Drawing Text - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)