#SVG tutorial for absolute beginners

##For who is this tutorial?
For people who have never seen a line of code in their life but would like to see a simple langauge used to draw stuff and have the possibility of learning animations.

## SVG is:
 - Scalable Vector Graphics
  - Meaning it scales to any resolution nicely and written in math terms
   - Don't worry it's not that much math as long as you know how to graph on an XY Plane you'll do fine.

## SVG is not:
 - Easy to write by hand (That's why you are reading this)
 - Frightening if you take your time like any other language

##Let's just dive into it
```HTML
<svg width="100" height="100">
    <circle cx="50" cy="50" r="40" stroke="black" stroke-width="1" fill="white" />
</svg>
```
Renders to:

![](1.png)
### Wait what?
Let's just dissect this part
```HTML
<svg width="100" height="100">
    ...
</svg>
```
Alright so what we have here is ``<SVG some other stuff here>`` and ``</svg>`` 

This is how we describe that we are starting an SVG file. This is important because it lets the computer know when to start and stop thinking in terms of SVG.

This is similar to HTML in that it uses the basic syntax of ``<some-tag-here></close-with-that-same-tag-here>``

Also it allows for properties on each tag in the format. ``<tag property="value"></tag>`` The "property"s are special words that are options on the tag being set to a specific value.

Anything that is apart of the SVG tag is an option that you are setting to it so
```HTML
<svg width="100" height="100">
    ...
</svg>
```
Width and height are options to SVG that we are telling the computer to realize. We set the width and height to specify a sort of "canvas" to SVG. Telling the computer we plan to draw within the bounds of 100 pixels in width and 100 pixels in height.

Now we have this as our file
```HTML
<svg width="100" height="100">
    
</svg>
```
But it only renders to:

![](Screenshot_1.png)

Well that's not very useful Let's [add some commands to it.](Circles.md)

