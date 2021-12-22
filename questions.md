# Hello

Write a Java program to print 'Hello' on screen and then print your name on a separate line.

Expected Output:

```bash
Hello
Samuel Bangari
```

_Themes: main method, compiling code, print statement_

# Intro

Write a Java program to print out about yourself. Please include your name, where you are from, what you do and an interesting thing about you. Feel free to get as creative as you like!

Expected Output:

```
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Hi, nice to meet you!
I'm Samuel from India. I moved to Japan 3 years ago.
I'm currently planting a church in Shibuya and 
also work in the Financial services industry in Tokyo.
I love cycling, coffee and Christ (but not in that order!)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

# Add Two

Write a method that sums two numbers. The program should define two variables to store the two numbers and a third variable to store the result of the summation. These three variables should be used while printing the output.

Expected Output:

```bash
Sum of 1 and 2 is 3
```

_Themes: variables, string formatting_

# Multiply Two

Write a Java program that takes two numbers as input and display the product of two numbers.

Expected Input:

```bash
Input first number: 25
Input second number: 5
```

Expected Output:

```bash
25 x 5 = 125
```

_Themes: reading input_

# Circle

Given the radius of a circle (r), write a Java program to print the area and perimeter of the circle. You can use the following formulae:

```
Area = PI * r * r
Perimeter = 2 * PI * r
```

You can assume that the value of PI is 3.14

Expected Input:

```bash
Radius: 7.5
```

Expected Output:

```bash
Perimeter is = 47.1
Area is = 176.625
```

_Themes: floating point arithmetic_

# Inches to Meters

Write a Java program that reads a number in inches, converts it to meters and displays it to second digit precision (0.00).
Note: One inch is 0.0254 meters.

Expected Input:

```
Enter the value in inches: 15
```

Expected Output:

```bash
15 inches is 0.38 meters
```

_Themes: floating point formatting_

# Iterations

Calculate how many times will `foo()` be executed:

```Java
for (int i = 0; i < 10; i++) {
  foo();
}
```

```Java
for (int i = 0; i < 10; i = i + 2) {
  foo();
}
```

```Java
for (int i = 10; i > 1; i = i - 2) {
  foo();
}
```

```Java
for (int i = 0, j = 10; i < 10 && j > 5; i++, j--) {
  foo();
}
```

```Java
for (int i = 0; i < 10;) {
  foo();
}
```

```Java
for (int i = 4; i < 20; i = 2 * i + 3) {
  foo();
}
```

```Java
for (int i = 0; i < 10; i++) {
  for (int j = 0; j < 10; j++) {
    foo();
  }
}
```

# Sum 1 to N

Given an input n, write a Java program to calculate the sum of integers 1, 2, 3, ... n.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of numbers 1 to 10 = 55
```

_Themes: loop_

# Sum Odd

Given an input n, where n is an odd number, write a program to calculate the sum of odd integers up to n: 1, 3, 5, ... n.

Expected Input:

```bash
Input Number: 11
```

Expected Output:

```bash
Sum of odd numbers from 1 to 11 is 36
```

# Sum Even

Given an input n, where n is an even number, write a program to calculate the sum of odd integers up to n: 2, 4, 6, ... n.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of odd numbers from 2 to 10 is 30
```

# Sum Squares

Given an input n, write a program to calculate the sum of squares of integers up to n: 1^2 + 2^2 + 3^2 + ... + n^2.

Expected Input:

```bash
Input Number: 10
```

Expected Output:

```bash
Sum of squares of numbers from 1 to 10 is 385
```

# Product 1 to N

Write a program called Product1ToN to compute the product of integers from 1 to 10 (i.e., 1x2x3x...x10), as an integer. Take note that it is the same as factorial of N.

Expected Input:

```bash
Input N: 10
```

Expected Output:

```bash
3628800
```

# Fibonacci

Write a Java program to accept a number n and print all the Fibonacci numbers in the increasing order less than n (inclusive).

Expected Input:

```bash
Enter a number n: 20
```

Expected Output:

```bash
1, 1, 2, 3, 5, 8, 13
```

# Sum and Average

Write a program in Java to input 5 numbers from keyboard and find their sum and average.

Expected Input:

```bash
Input the 5 numbers:                                                            
1                                                                                
2                                                                                
3                                                                                
4                                                                                
5                                                                                
```

Expected Output:

```bash
The sum of 5 no is : 15                                                          
The Average is : 3.0
```

# Maximum

Write a program in Java to input 2 numbers from keyboard and print the maximum.

Expected Input:

```bash
Input the two numbers:
3
6
```

Expected Output:

```bash
Maximum: 6
```

Now modify the program to make it work for 3 numbers

Expected Input:

```bash
Input the three numbers:
3
10
6
```

Expected Output:

```bash
Maximum: 10
```

Now modify the program to make it work for n numbers, where n is also an input

Expected Input:

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

```bash
Maximum: 6
```

Now modify the program to make it print the minimum as well.

Expected Input:

```bash
Input n: 4
Input the 4 numbers:
4
5
2
6
```

Expected Output:

```bash
Maximum: 6
Minimum: 2
```

# Even or Odd

Write a Java program to accept a number and check if it is even or odd. The program should print EVEN if the number is even and ODD if the number is odd.

Expected Input (even):

```bash
Input a number: 20
```

Expected Output:

```bash
EVEN
```

Expected Input (odd):

```bash
Input a number: 21
```

Expected Output:

```bash
ODD
```

_Themes: modulo_

# Sum of Digits

Write a Java program and compute the sum of the digits of an integer.

Expected Input:

```bash
Input an integer: 25
```

Expected Output:

```bash
The sum of the digits is: 7
```

# Change

Write a Java program to calculate optimal change for a given amount of currency in Japanese Yen.

Expected Input:

```bash
Input value (Japanese Yen): 2356
```

Expected Output:

```bash
10,000: 0
5,000: 0
1,000: 2
500: 0
100: 3
50: 1
10: 0
5: 1
1: 1
```

# Seconds

Write a Java program to convert seconds to hours, minutes and seconds.

Expected Input:

```bash
Input seconds: 86399    
```

Expected Output:

```bash
23:59:59
```

# Find in Array

Write a method that returns the index of the first occurrence of given integer in an array.
Assume that the index of the first element in the list is zero.
If the number does not exist return -1.
Ask the user for the array size and fill it with random integers from 0 to 100.

Expected Input:

```
Input a value for array size: 10
Input an integer: 5
```

Expected Output (if found):

```
6
```

Expected Output (if not found):

```
-1
```

_Themes: arrays_

# Array Sum

Write a program to display the sum of values in an array.
Ask the user for the array size and fill it with random integers from 0 to 100.

Expected Input:

```
Input a value for array size: 5
```

Expected Output:

```
Array: 4, 56, 1, 3, 6
Sum of values: 70
```

# Min and Max

Write a program to display the minimum and maximum values in an array.
Ask the user for the array size and fill it with random integers from 0 to 100.

Expected Input:

```
Input a value for array size: 5
```

Expected Output:

```
Array: 4, 56, 1, 3, 6
Minimum: 1
Maximum: 56
```

# Array Reverse

Write a program to create a new array which contains the the values in the original array, but in reverse order.
Ask the user for the array size and fill it with random integers from 0 to 100.

Expected Input:

```
Input a value for array size: 5
```

Expected Output:

```
Original: 4, 56, 1, 3, 6
Reversed: 6, 3, 1, 56, 4
```

# Array Multiply

Write a program to display the product of values in an array.
Ask the user for the array size and fill it with random integers from 0 to 100.

Expected Input:

```
Input a value for array size: 5
```

Expected Output:

```
Array: 4, 56, 1, 3, 6
Sum of values: 4032
```

# Array Digit Sum

Consider a numbering system where digits of a number are represented as arrays. For example, the number 35723 is represented as an array of 5 elements: 3-5-7-2-3. Write a program which takes two numbers n and m which represent the lengths of two arrays respectively. The program has to generate n and m sized arrays using Random and output a third array which contains the summation of the first two arrays.


Expected Input:

```
Input the size of first number: 5
Input the size of second number: 5
```

Expected Output:

```
First Array: 4, 6, 1, 3, 6
Second Array: 6, 3, 5, 7, 8
Summation Array: 1, 0, 9, 7, 1, 4
```

# String Reverse

Write a program to display the input string in reverse. The program should create a variable to store the string obtained from the user and then create another variable to store the reversed string.

Expected Input:

```
Input a string: The quick brown fox
```

Expected Output:

```
Reverse string: xof nworb kciuq ehT
```

_Themes: strings_

# Middle Character

Write a Java method to display the middle character of a string.
Note: 
a. If the length of the string is odd there will be two middle characters.
b. If the length of the string is even there will be one middle character.

Expected Input:

```
Input a string: Hello
```

Expected Output:

```
The middle character in the string: l
```

# Palindrome

A palindrome is a word which reads the same backward or forward. 'abcba' is a palindrome.
Write a method that detects if a string is a palindrome.
Tip: Use `word.charAt(i)` to get the character at position i.

Expected Input 1:

```
Input a string: racecar
```

Expected Output 1:

```
"racecar" is a palindrome
```

Expected Input 2:

```
Input a string: automobile
```

Expected Output 2:

```
"automobile" is not a palindrome
```

# Ceasar Cipher

The Ceasar cipher is a basic encryption technique used by Julius Ceasar to securely communicate with his generals. Each letter is replaced by another letter N positions down the english alphabet. For example, for a rotation of 5, the letter 'c' would be replaced by an 'h'. In case of a 'z', the alphabet rotates and it is transformed into a 'e'.

Implement an encoder and a decoder for the Ceasar cipher where N = 5.

TIP: Use code.toCharArray() to get an array of characters.

## Encoder

Expected Input:

```
Input a string: hello
```

Expected Output:

```
mjqqt
```

## Decoder

Expected Input:

```
Input a string: mjqqt
```

Expected Output:

```
hello
```

# Transpose

The musical scale follows the order: A, A#, B, C, C#, D, D#, E, F, F#, G, G#
Implement a transpose method which takes an integer (+ or -) and an input chord sequence and transposes the sequence to the right key.

Expected Input:

```
Chord Sequence: G, E, C, D
Transpose Value: 3
```

Expected Output:

```
Transposed Chord Sequence: A#, G, D#, F
```

# Harmonic Sum

Write a program called HarmonicSum to compute the sum of a harmonic series to 3rd decimal precision, as shown below.

```
Harmonic(n) = 1 + 1/2 + 1/3 + ... + 1/n
```

where n = 50000

Expected Input:

```
Enter the value of n: 50000
```

Expected Output:

```
Harmonic(50000): 11.397
```

# Compute PI

Write a program to compute the value of pi to 3rd digit precision, using the following series expansion. Use the maximum denominator (maxDenominator) as the terminating condition. Try maxDenominator of 100001.

```
pi = 4 * (1 - 1/3 + 1/5 - 1/7 + 1/9 - 1/11 + 1/13 - 1/15 + ... + 1/maxDenominator)
```

Expected Input:

```
Enter the value of maxDenominator: 100001
```

Expected Output:

```
Value of pi: 3.141
```

# Patterns

Write a program that prompts user for size (a non-negative integer in int); and prints the following patterns using two nested for-loops.

Expected Input:

```
Enter the size: 5
```

Expected Output:

```
# # # # #
# # # # #
# # # # #
# # # # #
# # # # # 
Square Pattern

# # # # # 
 # # # # #
# # # # # 
 # # # # #
# # # # # 
Checker Pattern

#
# #
# # #
# # # #
# # # # #
---------
# # # # #
# # # #
# # #
# #
#
---------
# # # # #
  # # # #
    # # #
      # #
        #
---------
        #
      # #
    # # #
  # # # #
# # # # #
Triangular Patterns

# # # # #
#       #
#       #
#       #
# # # # #
---------
# # # # #
  #
    #
      #
# # # # #
---------
# # # # #
      #
    #
  #
# # # # #
---------
# # # # #
  #   #
    #
  #   #
# # # # #
---------
# # # # #
# #   # #
#   #   #
# #   # #
# # # # #
Box Patterns

        #
      # # #
    # # # # #
  # # # # # # #
# # # # # # # # #
-----------------
# # # # # # # # #
  # # # # # # #
    # # # # #
      # # #
        #
-----------------
        #
      # # #
    # # # # #
  # # # # # # #
# # # # # # # # #
  # # # # # # #
    # # # # #
      # # #
        #
-----------------
# # # # # # # # #
# # # #   # # # #
# # #       # # #
# #           # #
#               #
# #           # #
# # #       # # #
# # # #   # # # #
# # # # # # # # #
Hill Patterns

1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
---------
1 2 3 4 5
  1 2 3 4
    1 2 3
      1 2
        1
---------
        1
      2 1
    3 2 1
  4 3 2 1
5 4 3 2 1
---------
5 4 3 2 1
4 3 2 1
3 2 1
2 1
1
Number Patterns
```

# Array Class

Create a class Array which:
1. Consumes the size in the constructor and prefills it with random numbers from 0 to 100. The size needs to obtained from the user.
2. Implements `Array.print()` method, which prints the contents of the array in a single line, separated by `,`.

Expected Input:

```
Input a value for array size: 5
```

Expected Ouptut:

```
Array: 3, 66, 90, 4, 12
```

3. Implements `Array.getSum()`, which returns the sum of values in the array.
4. Implements `Array.getAverage()`, which returns the average of the values in the array.
5. Implements `Array.getProduct()`, which returns the product of the values in the array.
6. Implements `Array.getMinimum()` and `Array.getMaximum()`, which return the minimum and maximum values in the array respectively.

Expected Ouptut:

```
Sum: 175
Average: 35
Product: 855360
Maximum: 90
Minimum: 3
```

7. Implements `Array.find(int key)`, which checks if `key` is present in the array and returns its index and `-1` otherwise.

Expected Input:

```
Input a value for key: 3
```

Expected Ouptut:

```
3 is present in the array at index 0
```

Expected Input:

```
Input a value for key: 5
```

Expected Ouptut:

```
5 is not present in the array
```
