# This is my first repo
#how to build simple calculater in python.

print('''
+ add
- substract
* multiply
% divide
''')

num1 = int(input("enter the value1:-"))
num2 = int(input("enter the value2-"))
opr = input("enter the opretor-")

if opr == "+":
    print(num1 + num2)
elif opr == "-":
    print(num1 - num2)
elif opr == "*":
    print(num1 * num2)
elif opr == "/":
    print( num1 / num2)
else:
    print("invalid opr...")
