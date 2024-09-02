Topic – 1: Introduction to Python
Introduction
Python is a versatile, high-level programming language known for its simplicity and readability. It is widely used in various fields, such as web development, data science, artificial intelligence, and automation. Python's syntax is clear and concise, making it an excellent choice for beginners and experienced developers alike. This repository contains a series of basic Python programs that introduce fundamental programming concepts.

Programs
1. Print a Message on Screen
This simple program prints a message on the screen, demonstrating how to use the print() function in Python.

# Program 1: Print a message on the screen
message = "Hello, World!"
print(message)

2. Arithmetic Operations (Summation, Subtraction, Multiplication, Division)
This program takes two numbers as input from the user and performs basic arithmetic operations such as summation, subtraction, multiplication, and division.

# Program 2: Perform arithmetic operations
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

sum_result = num1 + num2
sub_result = num1 - num2
mul_result = num1 * num2
div_result = num1 / num2

print(f"Summation: {sum_result}")
print(f"Subtraction: {sub_result}")
print(f"Multiplication: {mul_result}")
print(f"Division: {div_result}")


3. Area and Perimeter of a Circle
This program calculates the area and perimeter of a circle given its radius. It uses the formulas area = 3.14 * r * r and perimeter = 2 * 3.14 * r.

# Program 3: Calculate area and perimeter of a circle
import math

radius = float(input("Enter the radius of the circle: "))

area = 3.14 * radius * radius
perimeter = 2 * 3.14 * radius

print(f"Area: {area}")
print(f"Perimeter: {perimeter}")

4. Volume and Surface Area of a Cuboid
This program calculates the volume and surface area of a cuboid. The formulas used are volume = l * b * h and surface area = 2 * (l * b + b * h + h * l).

# Program 4: Calculate volume and surface area of a cuboid
length = float(input("Enter the length of the cuboid: "))
breadth = float(input("Enter the breadth of the cuboid: "))
height = float(input("Enter the height of the cuboid: "))

volume = length * breadth * height
surface_area = 2 * (length * breadth + breadth * height + height * length)

print(f"Volume: {volume}")
print(f"Surface Area: {surface_area}")


5. Simple Interest
This program computes the simple interest using the formula SI = (P * R * T) / 100.

# Program 5: Calculate simple interest
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the rate of interest: "))
time = float(input("Enter the time (in years): "))

simple_interest = (principal * rate * time) / 100

print(f"Simple Interest: {simple_interest}")

6. Square Root of a Number
This program calculates the square root of a given number using the math.sqrt() function.

# Program 6: Find the square root of a number
import math

number = float(input("Enter the number: "))
square_root = math.sqrt(number)

print(f"Square Root: {square_root}")


7. Convert Days into Years, Weeks, and Days
This program converts a given number of days into years, weeks, and days. It assumes a year has 365 days and does not account for leap years.

# Program 7: Convert days into years, weeks, and days
days = int(input("Enter the number of days: "))

years = days // 365
weeks = (days % 365) // 7
remaining_days = (days % 365) % 7

print(f"{years} years, {weeks} weeks, and {remaining_days} days")

8. Area and Perimeter of a Rectangle
This program calculates the area and perimeter of a rectangle given its length and breadth. The formulas used are area = l * b and perimeter = 2 * (l + b).

# Program 8: Calculate area and perimeter of a rectangle
length = float(input("Enter the length of the rectangle: "))
breadth = float(input("Enter the breadth of the rectangle: "))

area = length * breadth
perimeter = 2 * (length + breadth)

print(f"Area: {area}")
print(f"Perimeter: {perimeter}")


Conclusion
These programs provide a solid foundation in Python programming, covering basic operations, geometry, and mathematical computations. They are designed to help beginners gain confidence in writing and understanding Python code.

License
This project is licensed under the MIT License - see the LICENSE file for details.
