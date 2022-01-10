# Drawind coloring


import turtle
t = turtle.Pen()
colors = ["red","black","yellow","green"]
for x in range(100):
    t.pencolor(colors[x%4])
    t.forward(x)
    t.left(92)
    
