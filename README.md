# Feladat
import turtle               
wn = turtle.Screen()        
alex = turtle.Turtle()      
def sokszog(n, h, sz):
    for i in range(n):
        alex.color(sz)
        alex.forward(h) 
        alex.left(360/n)
        
        
sokszog(3, 50, "red")
sokszog(4, 50,  "blue")
sokszog(5, 50, "purple")
sokszog(6, 50, "green")
sokszog(7, 50, "white")
sokszog(8, 50, "pink")
sokszog(9, 50, "black")
sokszog(10, 50, "orange")
