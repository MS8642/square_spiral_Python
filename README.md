# square_spiral_Python
# Using Turtle module to draw a squared spiral in Visual Studio IDE.
import turtle 
square_spiral = turtle.Turtle() 
  
for i in range(3):
    square_spiral.forward(75) 
    square_spiral.left(90)

for i in range(2):
    square_spiral.forward(50)
    square_spiral.left(90)

for i in range(2):
    square_spiral.forward(25)
    square_spiral.left(90)

square_spiral.forward(10)
square_spiral.left(90)
square_spiral.forward(20)

     
turtle.done() 

# How it works: importing the "turtle" module
# will set the scene for a user to perform
# a simple drawing in the IDE.

# square_spiral is the variable where the new
# "turtle" object will be stored.
# The variable can be used to tell the 
# "turtle" how many pixels will the drawing 
# lines be (for example, square_spiral.forward(75))

# If you are facing a computer screen, .forward() command
# will draw the line from the middle of the drawing screen to 
# the right (e.g. ---------->)
# .left() means that the arrowhead will turn 90 degrees up and it will not draw anything (e.g. ^).

# To finish the drawing, "turtle.done()" specifies 
# that the drawing is done.
# Note: without "turtle.done()" at the end,
# the drawing board will close automatically
# as soon as the interpreter finishes reading
# the commands above.
