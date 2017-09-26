import math
import sys


def rectangle():
    heightRec = float(input("What is the Height of the Rectangle?"))
    widthRec = float(input("What is the Width of the Rectangle?"))
    AreaRec = heightRec * widthRec
    print("The Area of your Rectangle is", AreaRec)
    wow = input("Press 1 to go again, anything else to exit")
    if wow == "1":
        menu()
    else:
        exit()
def circle():
    radiusCir = float(input("What is the Radius of the Circle?"))
    AreaCir = math.pi * (radiusCir * radiusCir)
    print("The Area of your Circle is", AreaCir)
    wow = input("Press 1 to go again, anything else to exit")
    if wow == "1":
        menu()
    else:
        exit()
def triangle():
    heightTri = float(input("What is the Height of the Triangle?"))
    baseTri = float(input("What is the Base of the Triangle?"))
    AreaTri = (baseTri * heightTri) / 2
    print("The Are of your Triangle is", AreaTri)
    wow = input("Press 1 to go again, anything else to exit")
    if wow == "1":
        menu()
    else:
        exit()
def menu():
    print("WELCOME TO THE AREA CALCULATOR!")
    print("Which shape would you like to calcuate?")
    choice = input("1 = Rectangle, 2 = Circle, 3 = Triangle")
    if choice == "1":
        rectangle()
    elif choice == "2":
        circle()
    elif choice == "3":
        triangle()
    else:
        print("No comprendo mi amigo")
        menu()


menu()


    
