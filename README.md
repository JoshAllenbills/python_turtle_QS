import turtle
t = turtle.Turtle()
t.shape(name="turtle")

t.speed(0) # 1:slowest, 3:slow, 5:normal, 10:fast, 0:fastest
t.forward(100)
t.left(90)
t.forward(100)
t.left(90)
t.forward(100)
t.left(90)
t.forward(100)

for i in range(1500):
  t.forward(i)
  t.left(2)
  t.left(500)
