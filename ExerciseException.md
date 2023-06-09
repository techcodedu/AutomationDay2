Step 1: Create a new class
* Create a new Java class called ExceptionExercise in the default package.

Step 2: Define a method to get the input
* Define a static method called getNumber that takes a Scanner object and a String message as parameters, and returns an int.

* The method should prompt the user to enter an integer using the given message, and use a while loop to validate the input. If the input is not a valid integer, it should print an error message and prompt the user to enter a new input. Once the input is valid, it should return the integer.

Step 3: Define a method to calculate the average
* Define a static method called calculateAverage that takes three int parameters and returns a double.

* The method should check if any of the parameters are zero. If any of the parameters are zero, it should throw an ArithmeticException. If all the parameters are valid, it should calculate the average and return the result.

Step 4: Use try-catch blocks in the main method
* In the main method, use a try-catch block to handle exceptions that may occur when getting the input or calculating the average. If the input is not a valid integer, the NumberFormatException catch block should execute, and print a message to the console informing the user that the input is invalid. If the user tries to divide by zero, the ArithmeticException catch block should execute, and print a message to the console informing the user that division by zero is not allowed. If one or more of the numbers are missing, the NullPointerException catch block should execute, and print a message to the console informing the user that one or more numbers are missing.

Step 5: Test the program
* Test the program by running it and entering different inputs, including missing or zero values. Verify that the program handles these scenarios gracefully and prints informative error messages.

Step 6: Submit the program
* Submit the ExceptionExercise.java file to your instructor for review.

Sample Output:

<small>
<strong>Example 1: Valid input</strong>

Enter the first number: 5<br>
Enter the second number: 10<br>
Enter the third number: 15<br>
Average: 10.0<br><br>

<strong>Example 2: Invalid input</strong>

Enter the first number: abc<br>
Error: Invalid input. Please enter an integer.<br>
Enter the first number: 5<br>
Enter the second number: xyz<br>
Error: Invalid input. Please enter an integer.<br>
Enter the second number: 10<br>
Enter the third number: 15<br>
Average: 10.0<br><br>

<strong>Example 3: Missing input</strong>

Enter the first number: 5<br>
Enter the second number: <br>
Error: One or more numbers are missing.<br><br>

<strong>Example 4: Zero input</strong>

Enter the first number: 5<br>
Enter the second number: 0<br>
Error: Cannot divide by zero.<br>

</small>
