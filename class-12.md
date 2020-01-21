# Canvas

* Canvas is very similar to the image tag, except it does not take in a src or alt attribute
* You can set the height and width attributes inside the canvas tag
* Canvas elements should be assigned an ID for easier identification.
* Unlike the image tag, the canvas tag requires a closing `</canvas>` tag.
* The `<canvas>` element creates a fixed-size drawing surface that exposes one or more **rendering contexts**, which are used to create and manipulate the content shown.
* The `<canvas>` element has a method called `getContext()`, used to obtain the rendering context and its drawing functions.
    * takes in one argument, such as '2d'.
* Normally 1 unit on the grid, corresponds to 1 pixel on the canvas.
* Canvas only supports two primitive shapes, rectangles and paths.
* You can draw shapes by building and connecting paths.
    * Using paths you can incorperate lines, arcs, quadratic curves and rectangles.
* You can apply color to drawings using fillStyle and strokeStyle.
* You can also add transparency using the globalAlpha property.
* There several properties which allow us to style lines.
    * lineWidth
    * lineCap
    * lineJoin
    * miterLimit
    * getLineDash
    * setLineDash
    * lineDashOffset
