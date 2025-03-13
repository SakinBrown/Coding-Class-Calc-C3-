# Coding-Class-Calc-C3-
#Calculator - Sakin Brown

Include this one below -!
                        v

while True:
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    symbol = input("Enter symbol: ")

    #Addition
    if symbol == "+":
        def add(a, b):
            add = a + b
            print(add)
        add(a, b)
    
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    elif symbol == "-":
        def subtract(a, b):
            subtract = a - b
            print(subtract)
        subtract(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Subtraction
    elif symbol == "*":
        def multiply(a, b):
            multiply = a * b
            print(multiply)
        multiply(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Multiplication
    elif symbol == "/":
        def divide(a, b):
            divide = a / b
            print(divide)
        divide(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Devision
    elif symbol == "%":
        def modulas(a, b):
            modulas = a % b
            print(modulas)
        modulas(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Modulas
    elif symbol == "**":
        def exponent(a, b):
            exponent = a ** b
            print(exponent)
        exponent(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Exponent
    elif symbol == "//":
        def floor(a, b):
            floor = a // b
            print(floor)
        floor(a, b)
        another_calculation = input("Would you like to do another calculation? (yes or no) ")
        if another_calculation == "yes":
            continue
        else:
            break
    #Floor Devision
