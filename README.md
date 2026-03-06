# Calculator
Codsoft
# Simple Calculator Program

# Input two numbers
num1 = float(input("\n # Enter first number: "))
# Display operation choices
print("\n Choose an operation:")
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Division (/)")

# Input choice
choice = input(" # Enter choice (1/2/3/4): ")

num2 = float(input("\n # Enter second number: "))

# Perform calculation
if choice == '1':
    result = num1 + num2
    print("\n Result:", result)

elif choice == '2':
    result = num1 - num2
    print("\n Result:", result)

elif choice == '3':
    result = num1 * num2
    print("\n Result:", result)

elif choice == '4':
    if num2 != 0:
        result = num1 / num2
        print("\n Result:", result)
    else:
        print("Error: Division by zero is not allowed")

else:
    print("Invalid choice")
