# Student-Validation-Programs-Repository
A repository containing three Python programs that demonstrate input validation using conditions and iteration.

## Description
This repository contains three programs:

- Problem 1: Validating Student Score and Assigning Grades
- Problem 2: Validating Phone Number Format
- Problem 3: Validating Email Address

The programs check whether the user's input is valid. If the input is invalid, the program displays an error message and asks the user to enter the value again.

## How to Run
1. Open the program.
2. Run the program.
3. Enter the required values.
4. If the input is invalid, enter a valid value when asked again.

## Input Needed
- Problem 1: Student score from 0 to 100.
- Problem 2: Phone number in `09XX-XXX-XXXX` format.
- Problem 3: Email address containing `@` and `.`.

## Sample Output

### Problem 1

Sample Run 1 (valid input):

Enter the student score: 85
Grade: B

Two options for sample run 2 (invalid input)

[1] Sample Run 2 (invalid input):

Enter the student score: 150
Invalid score! Please enter a number between 0 and 100.

[2] Sample Run 2 (invalid input): If concepts on iteration is already discussed

Enter the student score: 150
Invalid score! Please enter a number between 0 and 100.
Enter the student score: -10
Invalid score! Please enter a number between 0 and 100.
Enter the student score: 72
Grade: C

### Problem 2

Sample Run 1 (valid input):

Enter your phone number: 0912-345-6789
Phone number accepted: 0912-345-6789

Sample Run 2 (invalid input): If concepts on iteration is already discussed

Enter your phone number: 9123456789
Invalid format! Please enter your phone number in 09XX-XXX-XXXX format.
Enter your phone number: 09123-456-789
Invalid format! Please enter your phone number in 09XX-XXX-XXXX format.
Enter your phone number: 0912-345-6789
Phone number accepted: 0912-345-6789

### Problem 3

Sample Run 1 (valid input):

Enter your email: student@example.com
Email accepted: student@example.com

Sample Run 2 (invalid input):

Enter your email: studentexample.com
Invalid email! Please enter a valid email address.
Enter your email: student@com
Invalid email! Please enter a valid email address.
Enter your email: student@example.com
Email accepted: student@example.com

## Author
Name: Madidis, Jihad E.
Section: 8-Molave 
