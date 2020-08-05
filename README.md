import turtle
turtle.speed(0)
turtle.screensize(300,300,"black")
turtle.title("Sumaya Felic. Graphics program.")
turtle.showturtle()
turtle.pensize(5)
turtle.color("light green")
turtle.pendown()
def circle1():
  for x in range(0,20):
    turtle.forward(20)
    turtle.left(10)
    turtle.forward(20)
    turtle.left(10)
  return
def circle2():
  for y in range (0,20):
    turtle.forward(10)
    turtle.left(10)
    turtle.forward(10)
    turtle.left(10)
  return
for z in range(0,12):
  circle1()
  turtle.left(11)
  for a in range (0,10):
    circle2()
    turtle.left(30)

