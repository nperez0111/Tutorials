#Coloring with numbers

Before we go into actual colors we have to specify which way that we would like to color. Yes there are multiple ways.

 - Hexadecimal 
  - Example `#000000` or `#000` for black, `#FFFFFF` or `#FFF` for white
    - Why is it numbers?
    - [Is there math involved?](is-there-math-involved)
    - How do I get colors out of this?
    - What's with the different lengths?
 - RGB
  - Example `rgb(0,0,0)` for black, `rgb(255,255,255)` for white
   - Numbers again?
   - How does this one work?
 - RGBA
  - Example `rgba(0,0,0,1)` for black, `rgba(255,255,255,1)` for white
   - Isn't it the same as that other one?
   - So what's different

#Hexadecimal
``#FF0000`` is written in Hexadecimal which is a numbering system that can is used to represent colors as numbers. To write Hexadecimal colors you split up the numbers in pairs such as
``# FF 00 00``. Wait, FF isn't a number? What gives? Well Hexadecimal literally means numbering system of 16, we don't have numbers that go to 16 without repeating / wrapping around. Notice that 10 is just repeating counting as 1,2,3,4... in the ten's place. So, to get around this programmers decided to just use letters. 

##Counting goes more like this:
 Hexadecimal | Normal
 ------------|-------
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

##Why is it numbers?
Because programmers don't like coming up with names for every color you have ever seen in your life. Imagine `dark-red`, `darker-red`, `auburn`, `dark-auburn`,`light-dark-auburn`.
##Is there math involved
No.
##How do I get a color out of this?
Well once it's split up like ``# FF 00 00`` We know that FF the biggest number possible in terms of a two digit Hexadecimal number (Think of it as sort of like 99 where it is 1 away from a 3 digit number). The numbers are split up like this to specify how much of one color to use in this pattern ``# (Amount of Red) (Amount of Blue) (Amount of Green)``. Therefore ``#FF0000`` is "pure red" , ``#00FF00`` is "pure blue" ,``#0000FF`` is "pure Green" ,``#000000`` is "pure black" and ``#FFFFFF`` is "pure white" a shade of gray is when all values are the same such as ``#333333`` or ``#CCCCCC``.
##Some colors
Color | Hex | Actual color
----- | --- | ------------
Light Gray | ``#CCCCCC`` | ![](Screenshot_10.png)
Dark Gray | ``#333333`` | ![](Screenshot_11.png)
Bad Ass Green | ``#BADA55`` | ![](Screenshot_12.png)