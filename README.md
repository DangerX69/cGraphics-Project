------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
A PROJECT FOR COMPUTER GRAPHICS:

SUBMITTED BY:

BISWASH KHANAL

BCT 'A'

ACE077BCT034

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

COMPILED USING GCC 9.2 32-BIT

LINKER PARAMETERS: -static-libgcc -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

C++ 11

**if unable to compile the program, please run the executable directly**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Objective: Make a Win32 application with toolbar and selectable options to draw different shapes in a canvas

Planned features:

Line:

  1. Using DDA Algorithm. 
 
  2. Using Midpoint. 
 
  3. Using Parameterized technique.
 


Circle: 

  1. Directly Using equation. 

  2. Using Polar form. 
 
  3. Using Midpoint Algorithm.
 


Ellipse: 

  1. Directly Using equation. 
 
  2. Using Polar form. 
 
  3. Using Midpoint Algorithm.
 


Curves:
* Just making curve seemed underwhelming so i decided to make shapes filled with some curves in syllabus: 

  1. Draw a Square/rectangle using Hermitian curve. 
 
  2. Draw Rectangle/square using Bezier curve. 
 
  3. 5 points Cardinal Spline Curve.
 


Filling Algorithms: 

 1. Recursive.
    
 2. Non Recursive *Note: Filling doesnt work for areas with more than the integer limit pixels.
    


Clipping: 

 1. Circle Line Clipping.
 
 2. Rectangle Line Clipping.
 


Colors: *can add as many color as needed with 4 lines of code increased for each color currently supports :

 1. Pink.
    
 2. Green.
    
 3. Purple.
    
 4. Black.
    


Other functionalities include an option to clear the current canvas, save and load canvas and the ability to change the pointer cursor within the context 
of the application window ( Standard Arrow, Cross, or Hand)

----------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------
HOW TO USE DIFFERENT FUNCTIONS:

Line: Select the algorithm to be used for drawing the line, then simply click once on each of the two end points to draw the line.
Circle

Circle: Select the algorithm to be used for drawing of the circle, then click once to set the center, click again at a position to be set as the radius.

Ellipse: Similar to circle, first click to set the center, click the second time at the required y radius and x radius away from the center.

Curves: For drawing of rectangles using curves, give two points to specify the width of the rectangle, (height is set within the program)
        For 5 points cardinal spline curve, click 5 points ( 1 start point, 3 control points and an end point)
        
