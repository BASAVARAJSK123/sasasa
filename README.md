# sasasa 




import turtle

colors = ['red', 'purple', 'blue', 'green', 'orange', 'yellow']
t = turtle.Pen()
t.speed(0)

turtle.bgcolor('black')
for x in range(360):
	t.pencolor(colors[x%6])
	t.width(x//100 + 1)
	t.forward(x)
	t.left(59)


t=turtle.Turtle()
s=turtle.Screen()
s.bgcolor('black')
t.pencolor('white')
t.speed(0)

for i in range (150):
    t.circle(190-1,90)
    t.lt(98)
    t.circle(190-1,90)
    t.lt(18)

t.end_fill()

t=turtle.Turtle()
s=turtle.Screen()
s.bgcolor('black')
t.pencolor('white')
t.speed(0)

for i in range (150):
    t.circle(190-1,90)
    t.lt(98)
    t.circle(190-1,90)
    t.lt(18)

t.end_fill()
