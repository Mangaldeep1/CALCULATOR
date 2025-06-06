# CALCULATOR
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
op = input("Choose operation (+, -, *, /): ")

if op == '+':
    result = num1 + num2
elif op == '-':
    result = num1 - num2
elif op == '*':
    result = num1 * num2
elif op == '/':
    result = num1 / num2 if num2 != 0 else "Error: Division by zero"
else:
    result = "Invalid operation"

print("Result:", result)

