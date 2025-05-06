print("*** Simple Python Calculator ***\n");

num1_str = input("Please enter your first number: ");
num2_str = input("Please enter your second number: ");
operation = input("Please enter an operation: +, -, /, *: ");

print("\n");

#Check if a valid number was entered
try:
    #Convert string to float
    num1 = float(num1_str); 
    num2 = float(num2_str);

    #Check which operation was entered
    if operation == "+":
        #Output the calculation, convert float to string
        print("Output: " + str(num1 + num2));
    elif operation == "-":
        print("Output: " + str(num1 - num2));
    elif operation == "*":
        print("Output: " + str(num1 * num2));
    elif operation == "/":
        if num2 == 0:
            print("Error, unable to divide by 0.");
        else:
            print("Output: " + str(num1 / num2));
    else:
        #Operation entered was not a valid option
        print("Error, operation entered was not valid.");

except ValueError: #Throw error if a number was not entered   
    print("Error, Invalid input. Please enter numbers only.")
    
