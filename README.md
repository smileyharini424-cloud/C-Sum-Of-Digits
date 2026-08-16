# C Sum Of Digits

## Explanation

This program calculates the sum of all digits in an integer entered by the user.

For example:

12345 = 1 + 2 + 3 + 4 + 5 = 15

## Problem Statement

Write a C program to find the sum of the digits of a given integer.

## Features

- Accepts an integer
- Extracts individual digits
- Calculates the sum of digits
- Handles negative numbers
- Uses a while loop

## How It Works

The program reads an integer from the user.

The modulus operator (%) extracts the last digit.

The extracted digit is added to the sum.

The number is divided by 10 to remove the last digit.

This process continues until all digits have been processed.

## Technologies Used

- C
- GCC Compiler
- Code Editor

## Data Structure Used

No data structure is used.

## Methods Used

- main()
- printf()
- scanf()

## Control Structure Used

- while loop
- if statement

## Operators Used

- %
- /
- +
- =

## Program Flow

Start
↓
Read number
↓
Convert negative number if required
↓
Extract last digit
↓
Add digit to sum
↓
Remove last digit
↓
Repeat until number becomes zero
↓
Display sum
↓
End

## Sample Input

Enter an integer: 12345

## Sample Output

Sum of digits = 15

## Sample Input 2

Enter an integer: 908

## Sample Output 2

Sum of digits = 17

## Time Complexity

O(d)

where d is the number of digits in the number.

## Space Complexity

O(1)

## Key Learning

This program teaches how to extract individual digits and perform calculations on them using modulus and division operators.

## File Location

sum_digits.c

## Repository Structure

C-Sum-Of-Digits/
├── README.md
└── sum_digits.c

## Author

V.Harini
