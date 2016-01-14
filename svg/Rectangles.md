#Rectangles In SVG

Rectangles have a pretty basic [syntax](general/definitions.md#syntax):
```HTML
<rect width="75" height="30" x="10" y="15">
```
Renders to:

![](Screenshot_15.png)

##Let's get into it's properties

 - [`width` property](#width-property)
 - [`height` property](#height-property)
 - [`x` property](#x-property)
 - [`y` property](#y-property)
 - [`rx` property](#rx-property)
 - [`ry` property](#ry-property)

##Width property

It changes the width of the rectangle, but I think you guessed that one.

##Height property

Guess! Guess! Guess! You won't figure this one out! Let's move on.

##X property

This changes the X coordinate of the rectangle, but let's go a little more into how this calculated. The X Axis is actually the left-most edge of the canvas. This means that the x coordinate is actually specifying the space _<b>from the left edge of the canvas</b>_ (This is important because it is not very typical)

##Y Property

This changes the Y coordinate of the rectangle and is in reference to the top of the canvas or container.

##RX Property

This refers to the radius of the circle in terms of X of the rounding of the rectangle off on the corners.

##RY Property

Same as [`RX` property](#rx-prorperty) but for `Y`.

Bored of boring rectangles? [Let's get back into more fun shapes like ellipses](Ellipses.md)