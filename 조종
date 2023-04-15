import turtle as t


def fclick(x, y):
    t.fillcolor("red")


def frelease(x, y):
    t.fillcolor("skyblue")


def fup():
    t.forward(30)


def fdown():
    t.back(30)


def fleft():
    t.left(15)


def fright():
    t.right(15)


def main():
    t.bgcolor("wheat")
    t.pensize(3)
    t.speed(0)
    t.shapesize(1)
    t.shape("turtle")
    t.color("black", "skyblue")

    t.onscreenclick(t.goto)
    t.ondrag(t.goto)
    t.onclick(fclick)
    t.onrelease(frelease)
    t.onkey(fup, "Up")
    t.onkey(fdown, "Down")
    t.onkey(fleft, "Left")
    t.onkey(fright, "Right")
    t.listen()
    return


if __name__ == "__main__":
    main()
    t.mainloop()
