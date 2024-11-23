# Simple Calculator Program

# Ask the user for two numbers
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Ask the user for a mathematical operation
operation = input("Choose an operation (add, subtract, multiply, divide): ").strip().lower()

# Perform the selected operation and display the result
if operation == "add":
    result = num1 + num2
    print(f"The result of addition is: {result}")
elif operation == "subtract":
    result = num1 - num2
    print(f"The result of subtraction is: {result}")
elif operation == "multiply":
    result = num1 * num2
    print(f"The result of multiplication is: {result}")
elif operation == "divide":
    if num2 != 0:
        result = num1 / num2
        print(f"The result of division is: {result}")
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid operation. Please choose add, subtract, multiply, or divide.")

Enter the first number: 10  
Enter the second number: 5  
Choose an operation (add, subtract, multiply, divide): multiply  

The result of multiplication is: 50.0

