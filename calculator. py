def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Division by zero!"
    return a / b

def main():
    while True:
        print("\n--- CLI Calculator ---")
        print("1. Add")
        print("2. Subtract") 
        print("3. Multiply")
        print("4. Divide")
        print("5. Exit")
        
        choice = input("Enter choice 1-5: ")
        
        if choice == '5':
            print("Calculator closed. Bye Suva!")
            break
            
        if choice not in ['1','2','3','4']:
            print("Invalid choice! 1-5 mattum try pannu")
            continue
        
        try:
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
        except ValueError:
            print("Error: Number mattum enter pannu da")
            continue
        
        if choice == '1':
            print(f"Result: {num1} + {num2} = {add(num1, num2)}")
        elif choice == '2':
            print(f"Result: {num1} - {num2} = {subtract(num1, num2)}")
        elif choice == '3':
            print(f"Result: {num1} * {num2} = {multiply(num1, num2)}")
        elif choice == '4':
            print(f"Result: {num1} / {num2} = {divide(num1, num2)}")

if __name__ == "__main__":
    main()
