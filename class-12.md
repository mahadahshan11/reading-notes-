# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS

* 1) charts are the perfect tool to display visual data because they are easier to read data from, and procss data more quickly. hwever they are not easy to create.

* 2) to start using charts you need to start with  Chart.js, which is a javaScript plugin that uses HTML5's canvas element to draw the graph onto tje page. it uses all kinds of bar charts, line charts, pie charts, and more. 

* 3) to draw a chart in our web site we must first ao a set up and download chart.js copy and into the directory. then we must create a new HTML page and import the script in it. then we create a canvas element in our HTML page. then we need to write a script that will retrive the contxt of the canvas, and adding it to the foot of you HTML body. inside the script we need to create our data. 

* **
 # Canvas API

**Basic usage:**

 * 1)  The `<canvas>` element has only two attributes (width and height). they are both optional and also can be set using DOM properties. the default sitting with the canvas is 300px width and 150px height. it can be styled using CSS and selecting it by id. 

 * 2) The `<canvas>` element provide a straightforward fallback content to be displayed by older browsers of the Internet but with the necessity of a closing tag `</canvans>`.

 * 3) The `<canvas>` element creates a fixed-size drawing that shows one or more renderign contexts, which in turnes are used to created and manipulate the content shown. The canvans in initially blank. to display any content, a script first need to access the rendering context and draw on it. This achieved by bu a method called `getContext()`. 


**Drawing shapes with canvas**

* 1) before drawing comes the *The grid* which is the coordinate space. the default grid in the HTML skeleton is normally 1 unit in the grid for 1 px on the canvas. all the elements are placed relative to this origin which is set at the top left corner at coordinate (0,0).

* 2) Drawing rectangles: by using one of thses three finctions, [`fillRact (x, y, width, height)`] To draw a filled rectangle. [`strokeRect (x, y, width, height)`] To draw a rectangular outline. [`clearRect(x, y, width, height)`] To draw a transparent rectangle area.

* 3) To draw paths we use thses steps: [begin path()/ closePaht()/ stroke()/ fill()]. 

**Applying styles and colors**

* 1) there are two important properties we can use: [`fillStyle = collor`] & [`strokestyle = color`]. 

**Drawing text**

* 1) There are two main methods to render a text. [`fillText(text, x,y, [, maxWidth])`] that fill a given text at the given (x,y) position. & [`strokeText (text, x, y, [,maxWidth])`] the gives text at given (x,y) position. 

