# ArteProgra_A1
Documentation of the code:

The given code is a Python program that uses the turtle graphics library to draw shapes on the screen. It defines several functions to draw different shapes, such as lines, squares, circles, rectangles, and triangles. It also defines a "tap" function that is called when the user clicks on the screen, which either stores the starting point of a shape or draws the shape using the current starting and ending points.

Here is a brief summary of each function:

* line(start, end): Draws a line from the start point to the end point.
* square(start, end): Draws a square from the start point to the end point.
* circle1(start, end): Draws a circle with its center at the start point and its radius determined by the distance between the start and end points.
* rectangle1(start, end): Draws a rectangle from the start point to the end point.
* triangle1(start, end): Draws a triangle from the start point to the end point.
* tap(x, y): Called when the user clicks on the screen. Stores the starting point of a shape if there is no existing starting point, or draws the current shape using the current starting and ending points.
* store(key, value): Stores the given value in the state dictionary at the given key.

The program also defines a state dictionary that keeps track of the current starting point and shape to be drawn. It sets the initial starting point to None and the initial shape to line. It sets up the screen using the setup function and sets up event listeners using the onscreenclick, listen, and onkey functions. Finally, it enters the event loop using the done function.
