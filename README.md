# My-1st-Repository-
Mini-Project (python-Calculator) By using Conditions...
# Lets build A Calculator
first = input("Enter first Number : ")
operator = input("Enter operator (+,-,*,/,% )")

second = input("Enter 2nd Number : ")
 
first = int(first)
second = int(second)

if operator == "+":
    print(first + second)

elif operator == "-":
    print(first - second)
    
elif operator == "*":
    print(first * second)
    
elif operator == "/":
    print(first / second)

elif operator == "%":
    print(first % second)
else:
    print("Invalid Operation")
