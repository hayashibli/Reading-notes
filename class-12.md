# Charts
Charts are better for displaying data than tables. There is something called *Chart.js* which makes using all kinds of charts easier. To draw any type of chart you need to add (script) element inside the head element and contain the source *Chart.min.js* , then you should create a (canvas) element into the body element of HTML.

**Canvas element**
This element is similar to (img) element but with different attributes including; the *width* , *height* and an *Id*. If width and height attributes weren't setted then by default the width will be 300px and the height will be 150px. Canvas element can be styled by css as an image (margin , border , background and different properties). Also, you can provide text description between the canvas opening and closing tags.  The (canvas) element has a method called *getContext()*, used to obtain the rendering context and its drawing functions and it takes one parameter, the type of context like (2d) to get a CanvasRenderingContext2D.

This element support two shapes : rectangle and paths (lists of points connected by lines) , other shapes are made by combining one or more paths. 
*There are three functions that draw rectangles on the canvas:*

- fillRect(x, y, width, height)
Draws a filled rectangle.
- strokeRect(x, y, width, height)
Draws a rectangular outline.
- clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

*Steps to draw paths*

- beginPath()
Creates a new path.
- Path methods
Methods to set different paths for objects.
- closePath()
Adds a straight line to the path, going to the start of the current sub-path.
- stroke()
Draws the shape by stroking its outline.
- fill()
Draws a solid shape by filling the path's content area.

*To draw lines*
lineTo(x, y).

*To draw arcs*
arc(x, y, radius, startAngle, endAngle, anticlockwise)

*To draw Bezier and quadratic curves*
quadraticCurveTo(cp1x, cp1y, x, y)
bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)

**Colors**
If you want to apply colors to a shape, there are two important properties :
- fillStyle = color
- strokeStyle = color

**Draw a text**
you can use :
- fillText(text, x, y [, maxWidth])
- strokeText(text, x, y [, maxWidth])

**Style a text**
yo can use :
- font = value
- textAlign = value
- textBaseline = value
- direction = value
- measureText()