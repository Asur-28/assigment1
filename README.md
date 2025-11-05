What it does

The program asks you to type two numbers.
It then shows four results:
Addition: the sum of the two numbers
Subtraction: the first number minus the second
Multiplication: the product of the two numbers
Division: the first number divided by the second

How it works (in simple words)
input(...) asks you to type something on the keyboard.
int(...) converts what you typed into whole numbers (integers).
a and b store those numbers.
a + b, a - b, a * b, a / b do the math.
print(...) shows the result on the screen.

Program 2: Greeting by Name
Code

python
a = input("enter your first name")
b = input("enter your last name")

print(f"\nHello, {a}{b}! welcome to the python program.")

What it does

The program asks you to type your first name and your last name.
It then greets you with a friendly message that includes your full name.
How it works 

input(...) asks for text and stores it in variables a (first name) and b (last name).
The f-string f"\nHello, {a}{b}! welcome to the python program." builds a sentence by putting your names where the braces are.
print(...) shows the greeting on the screen.
Important note
There is no space between the first name and the last name in the greeting. If you want a space, you can change the code to:
print(f"\nHello, {a} {b}! Welcome to the Python program.")
