# PongGame
# python 3 programming
# By @rick_simo
# Part 1 : Getting Started


import turtle 

wm = turtle.Screen ()
wm.title ("Pong by @rick_simo")
wm.bgcolor ("black")
wm.setup (width=800, height=600)
wm.tracer (0)

# Paddle A 

paddle_a = turtle.Turtle ()
paddle_a.speed (0)
paddle_a.shape ("square")
paddle_a.color ("white")
paddle_a.shapesize (stretch_wid=5, stretch_len=1)
paddle_a.penup ()
paddle_a.goto (-350,0)


# Paddle B

paddle_b = turtle.Turtle ()
paddle_b.speed (0)
paddle_b.shape ("square")
paddle_b.color ("white")
paddle_b.shapesize (stretch_wid=5, stretch_len=1)
paddle_b.penup ()
paddle_b.goto (350,0)


# Ball



# Main game loop
while True:
