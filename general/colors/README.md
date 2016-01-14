# Coloring with numbers

Before we go into actual colors we have to specify which way that we would like to color. Yes there are multiple ways.

 - Hexadecimal 
  - Example `#000000` or `#000` for black, `#FFFFFF` or `#FFF` for white
    - [Why is it numbers?](#why-is-it-numbers)
    - [Is there math involved?](#is-there-math-involved)
    - [How do I get colors out of this?](#how-do-i-get-colors-out-of-this)
    - [What is with the different lengths?](#what-is-with-the-different-lengths)
    - [Some example colors](#some-example-colors)
 - RGB
  - Example `rgb(0,0,0)` for black, `rgb(255,255,255)` for white
    - [Numbers again?](#numbers-again)
    - [How does this one work?](how-does-this-one-work)
 - RGBA
  - Example `rgba(0,0,0,1)` for black, `rgba(255,255,255,1)` for white
   - [Isn't it the same as that other one?](isn't-it-the-same-as-that-other-one)
   - [So what's different?](so-what's-different)

# Hexadecimal

``#FF0000`` is written in Hexadecimal which is a numbering system that can is used to represent colors as numbers. To write Hexadecimal colors you split up the numbers in pairs such as
``# FF 00 00``. Wait, FF isn't a number? What gives? Well Hexadecimal literally means numbering system of 16, we don't have numbers that go to 16 without repeating / wrapping around. Notice that 10 is just repeating counting as 1,2,3,4... in the ten's place. So, to get around this programmers decided to just use letters. 

## Counting goes more like this:

Hexadecimal | Normal
:------------:|:-------:
0 | 0
1 | 1
2 | 2
... | ...
9 | 9
A | 10
B | 11
C | 12
D | 13
E | 14
F | 15
10 | 16

## Why is it numbers?

Because programmers don't like coming up with names for every color you have ever seen in your life. Imagine `dark-red`, `darker-red`, `auburn`, `dark-auburn`,`light-dark-auburn`.

## Is there math involved?

No.

## How do I get a color out of this?

Well once it's split up like ``# FF 00 00`` We know that FF the biggest number possible in terms of a two digit Hexadecimal number (Think of it as sort of like 99 where it is 1 away from a 3 digit number). The numbers are split up like this to specify how much of one color to use in this pattern ``# (Amount of Red) (Amount of Blue) (Amount of Green)``. Therefore ``#FF0000`` is "pure red" , ``#00FF00`` is "pure blue" ,``#0000FF`` is "pure Green" ,``#000000`` is "pure black" and ``#FFFFFF`` is "pure white" a shade of gray is when all values are the same such as ``#333333`` or ``#CCCCCC``.

##What is with the different lengths?

Why are we allowed to use either `#000` or `#000000`? Well when you use 3 hexadecimal numbers like `#AB3` the computer already knows to expand it to six by repeating each number twice. Therefore, `#AB3` becomes `#AABB33`.

##Some example colors

Color | Hex | Actual color
----- | --- | ------------
Light Gray | ``#CCCCCC`` | ![](Screenshot_10.png)
Dark Gray | ``#333333`` | ![](Screenshot_11.png)
Bad Ass Green | ``#BADA55`` | ![](Screenshot_12.png)

# RGB
RGB is another way to specify colors but uses actual numbers and is split up a little more cleanly.

`RGB(0,0,0)` for black or `RGB(255,255,255)` for white.

## Numbers again?
YES! These numbers actually correspond exactly to hexadecimal. FF in hexadecimal numbering converts to 255 which is the max value RGB takes in for a single color.

## How does this one work?
RGB is meant to be a more readable way of using colors. 

RGB stands for:
 - Red
 - Green
 - Blue

And is used exactly in that order surrounded by parenthesis and separated by commas.

`RGB( Red , Green , Blue )`
# RGBA

## Isn't it the same as the other one?

You sure ask a lot of questions! Yes you are correct, it is the same as the other one with the added A and yet another number!

## So what's different

The A in RGBA means `alpha channel` and in plain English it means transparency. So the transparency factor allows you to show elements that overlap or if there is a dark background it will alow some of that color to "bleed" through.