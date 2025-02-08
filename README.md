while True:
    ch = int(input("Enter your choice:\n1. Fahrenheit to Celsius\n2. Celsius to Fahrenheit\n3. Exit\n"))
    
    if ch == 1:
        far = float(input("\nEnter the temperature in Fahrenheit: "))
        cel = (far - 32) * (5/9)
        print(f"\nThe temperature in Celsius is: {cel:.2f}°C")
    
    elif ch == 2:
        cel = float(input("\nEnter the temperature in Celsius: "))
        far = (cel * 9/5) + 32
        print(f"\nThe temperature in Fahrenheit is: {far:.2f}°F")
    
    elif ch == 3:
        break
    
    else:
        print("\nInvalid choice. Please enter 1, 2, or 3.")
