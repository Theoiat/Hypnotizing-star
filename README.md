#copycode Hypnotizing

import turtle 
t=turtle.Turtle()
colors = ['red', 'orange', 'yellow', 'green', 'blue', 'violet', 'aqua', 'blueviolet']
t.speed (0)
for i in range(1200):
  t.color(colors[i % 8])
  t.forward(i/2)
  t.left(140) 
  
  

