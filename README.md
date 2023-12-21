"""Welcome to the Calculator program!")
Select an operation to perform by inputting a number:
1. Addition
2. Subtraction
3. Multiplication
4. Division"""

operation = input("""Welcome to the Calculator program! 
1. Addition
2. Subtraction
3. Multiplication
4. Division
Select an operation to perform by inputting a number: """)

if operation == "1":
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(int(num1)+int(num2))
elif operation == "2":
    #subtraction
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(int(num1) - int(num2))
elif operation == "3":
    #multiplication
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(int(num1) * int(num2))
elif operation == "4":
    #division
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(int(num1) / int(num2))
else:
    print("Error: Please input a number that corresponds with the operations on the list")



