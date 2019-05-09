## Python turtle graphics & Scalable Vector Graphics
### Timothy Kerr
____

The purpose for this tutorial is to explain the basics and fundamentals of pythons
SVG (Scalable Vector graphics) called turtle. This tutorial will demonstrate a few
examples of turtle graphics and the controls you need as a coder to take the wheel
and get to drawing.

Some of the topics we will be covering
+ What is a SVG
+ The invention of SVG
+ Why SVG are useful
+ Pythons turtle
+ Controls, Colors and Gradients


##### What is a SVG ?
SVG stands for Scalable Vector Graphics. SVG is a vector graphic image file extension that
contains scalable images. This XML based file extension supports animation that
can contains vector graphics, raster graphics, and text.

![SVG Demo](https://cdn-images-1.medium.com/max/1600/1*7oUycpD-hOk8lJtirFo7mw.gif)



##### The invention of SVG
Scalable vector graphics was developed by the
 [World Wide Web Consortium](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)
. The project started in 1999 during an *"explosion of diffrent formats"* stated by W3C
 after six competing proposals for vectored graphics had been
submitted to the Consortium. And on September 4th 2001 the first iteration of SVG
was released, only to be upgraded to the second only revision on August 16th 2011


##### Why SVG is useful
Now I want you to take a screenshot of your computer screen and zoom in
if you have zoomed in far enough you notice how it looks pixelated:
![](https://cdn-images-1.medium.com/max/1600/1*KmNgIE8zhdLqznfnAuEW0w.png)

The zoomed in graphic looks pixelated because it is composed of individual,
square boxes, each containing a unique color.
Most of us are likely accustom to that exact word, pixelated.
This word actually has a technical origin. **Picture Elements**

![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Bitmap_VS_SVG.svg/300px-Bitmap_VS_SVG.svg.png)

Notice how the picture on the right is much more crisp and defined

Here is more information on [Picture Elements](https://en.wikipedia.org/wiki/Pixel)

SVG is useful because inseat of it being information telling you where to put these "pixels"
its composed of data that can expand and contrast without loss of data or the need to "guess"
where to put the pixels resulting in a low quality image.

![](https://engage-site-cms.s3.amazonaws.com/production/engage-interactive/cms/processed/1703c6b49e9f141c43dbef1922edf8e5.gif)

##### Pythons Turtle
“Turtle” is a python feature like a drawing board, which lets you command a turtle to draw all over it using simple commands!

You can use functions like turtle.forward(...) and turtle.left(...) which can move the turtle around.

Before you can use turtle, you have to import it. We recommend playing around
 with it in the interactive interpreter first, as there is an extra bit of work required to make it work from files.


##### Python Commands and Controls
Below I have linked a picture uploaded to imgur for you ease of use.
You can download it for reference [here](https://i.imgur.com/x2JzESd.png?1)
![here](https://i.imgur.com/x2JzESd.png?1)


Here is some examples of a RGB Helix drawn in Turtle, while it looks complicated it
is rather simple

When this is entered into python it produces a beautiful image.

````
# Python program to draw
# Spiral  Helix Pattern
# using Turtle Programming

import turtle
loadWindow = turtle.Screen()
turtle.speed(2)

for i in range(100):
    turtle.circle(5*i)
    turtle.circle(-5*i)
    turtle.left(i)

turtle.exitonclick()
````
![](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/tttttttttttttttttt5-1024x349.jpg)
