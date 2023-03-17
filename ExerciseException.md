Step 1: Create a new class
# Create a new Java class called ExceptionExercise in the default package.

Step 2: Define a method to get the input
# Define a static method called getNumber that takes a Scanner object and a String message as parameters, and returns an int.

# The method should prompt the user to enter an integer using the given message, and use a while loop to validate the input. If the input is not a valid integer, it should print an error message and prompt the user to enter a new input. Once the input is valid, it should return the integer.

Step 3: Define a method to calculate the average
# Define a static method called calculateAverage that takes three int parameters and returns a double.

# The method should check if any of the parameters are zero. If any of the parameters are zero, it should throw an ArithmeticException. If all the parameters are valid, it should calculate the average and return the result.

Step 4: Use try-catch blocks in the main method
# In the main method, use a try-catch block to handle exceptions that may occur when getting the input or calculating the average. If the input is not a valid integer, the NumberFormatException catch block should execute, and print a message to the console informing the user that the input is invalid. If the user tries to divide by zero, the ArithmeticException catch block should execute, and print a message to the console informing the user that division by zero is not allowed. If one or more of the numbers are missing, the NullPointerException catch block should execute, and print a message to the console informing the user that one or more numbers are missing.

Step 5: Test the program
# Test the program by running it and entering different inputs, including missing or zero values. Verify that the program handles these scenarios gracefully and prints informative error messages.

Step 6: Submit the program
# Submit the ExceptionExercise.java file to your instructor for review.

Sample Output:

Example 1: Valid input

Enter the first number: 5
Enter the second number: 10
Enter the third number: 15
Average: 10.0

Example 2: Invalid input

Enter the first number: abc
Error: Invalid input. Please enter an integer.
Enter the first number: 5
Enter the second number: xyz
Error: Invalid input. Please enter an integer.
Enter the second number: 10
Enter the third number: 15
Average: 10.0

Example 3: Missing input
Enter the first number: 5
Enter the second number: 
Error: One or more numbers are missing.

Example 4: Zero input
Enter the first number: 5
Enter the second number: 0
Error: Cannot divide by zero.

Sure! Here's an example of what the program output should look like for different input scenarios:

Example 1: Valid input

yaml
Copy code
Enter the first number: 5
Enter the second number: 10
Enter the third number: 15
Average: 10.0
Example 2: Invalid input

yaml
Copy code
Enter the first number: abc
Error: Invalid input. Please enter an integer.
Enter the first number: 5
Enter the second number: xyz
Error: Invalid input. Please enter an integer.
Enter the second number: 10
Enter the third number: 15
Average: 10.0
Example 3: Missing input

sql
Copy code
Enter the first number: 5
Enter the second number: 
Error: One or more numbers are missing.
Example 4: Zero input

yaml
Copy code
Enter the first number: 5
Enter the second number: 0
Error: Cannot divide by zero.
Example 5: Multiple missing and zero input
Enter the first number: 0
Error: Cannot divide by zero.


