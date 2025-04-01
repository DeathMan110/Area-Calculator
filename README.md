# Area-Calculator
print("Area Calculator 📐")
print("        ")
print("        ")

print("1) Triangle")
print("2) Rectangle")
print("3) Square")
print("4) Circle")
print("5) Quit")

shape = int(input("Which Shape:  "))
print("     ")
print("     ")
if shape == 3:
  side = int(input("Side: "))
  area = side**2
  print("The area is ", area)
elif shape == 4:
  radius = int(input("Radius:  "))
  area = 3.14*radius*radius 
  print("The area is ", area)
elif shape == 1:
  base = int(input("Base:  "))
  height = int(input("Height:  "))
  area = (base*height)/2
  print("The area is ", area)
elif shape == 2:
  base = int(input("Base:  "))
  height = int(input("Height:  "))
  area = height*base 
  print("The area is ", area)
